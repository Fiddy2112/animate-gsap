# GSAP Scroll Animation – Frame Sequence from Video

Dự án này tạo hiệu ứng **scroll animation** bằng cách hiển thị từng khung hình (frame)** tách ra từ video**. Khi người dùng cuộn, hình ảnh thay đổi liên tục tạo cảm giác như đang xem video chạy theo scroll.

## Công nghệ sử dụng

- **GSAP 3 + ScrollTrigger** – điều khiển animation theo scroll
- **Canvas API** – render từng frame
- **FFmpeg** – tách ảnh từ video
- **SheryExtract** – extract video frames chất lượng cao
- **TailwindCSS (CDN)** – layout nhanh
- **Local Server (Live Server / Node / Python)** – bắt buộc để load ảnh

---

## Cấu trúc thư mục

```bash
    project/
    │
    ├── index.html
    ├── animate/
    │ ├── frame_0001.jpeg
    │ ├── frame_0002.jpeg
    │ ├── frame_0003.jpeg
    │ └── ...
    └── README.md
```

> Các ảnh cần đặt đúng format:
>
> `frame_0001.jpeg → frame_00XX.jpeg`

---

### Dùng FFmpeg

cài : ```bash
ffmpeg.msi

````

## Tách ảnh từ video

chạy :

```bash
    SheryExtract.exe
```
````
