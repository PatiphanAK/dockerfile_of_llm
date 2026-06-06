# วิธีใช้งาน Image นี้
```
docker run --gpus all -p 8000:8000 your-image-name
```

ใส่ flag --gpus ด้วยเพราะอนุญาตให้ Container มองเห็นและสิทธิ์ในการใช้งานการ์ดจอ (GPU) ของเครื่อง Host ได้
