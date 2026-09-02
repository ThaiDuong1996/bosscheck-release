# Boss Check — kênh phát hành

Repo này **chỉ chứa file phát hành**, không có mã nguồn.

| File | Việc |
|---|---|
| `version.json` | App đọc file này để biết có bản mới không |
| `blacklist.json` | Danh sách mã máy bị khoá |

Bản cài đặt nằm ở mục [Releases](../../releases).

## Quy trình phát hành

Chạy ở thư mục dự án:

```
python build.py --bump patch
python release.py
```

Rồi làm theo hướng dẫn nó in ra.
