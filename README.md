# Dich Thuat Busan - Static Website

Website tinh duoc tao tu dong tu Laravel app bang `generate_static.py`.

## Deploy len GitHub Pages

1. Push thu muc `static_web/` len GitHub repo
2. Vao Settings -> Pages -> Source: chon branch va thu muc
3. Truy cap tai `https://<username>.github.io/<repo>/`

## Cap nhat noi dung

1. Chinh sua qua Admin Panel: http://localhost:8080/admin
2. Chay lai: `python3 generate_static.py`
3. Commit & push `static_web/`

## Luu y

- Form lien he bi vo hieu hoa tren phien ban tinh
- Chuc nang admin chi hoat dong tren Laravel app (Docker)
