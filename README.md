# Vach Chia O CAD

Cong cu thiet ke vach chia o, xem truoc ban ve va xuat file CAD DXF.

## Tinh nang

- Nhap thong so va so luong o vach.
- Xem truoc ban ve truc quan.
- Xuat ban ve dinh dang DXF de mo bang phan mem CAD tuong thich.
- Giao dien ho tro may tinh va dien thoai.
- Ho tro cai dat len man hinh chinh tren iPhone va Android thong qua PWA.
- Ho tro cache tai nguyen de co the mo lai giao dien sau khi da truy cap thanh cong.

## Cau truc du an

```text
.
├── index.html
├── manifest.webmanifest
├── sw.js
├── README.md
├── DOC_CAI_DAT.txt
└── icons/
    ├── icon-192.png
    └── icon-512.png
```

## Chay tren may tinh

Mo `index.html` bang trinh duyet de su dung giao dien.

Luu y: tinh nang cai dat PWA va service worker can website chay qua HTTPS hoac localhost. Mo file HTML truc tiep tu may tinh khong kich hoat day du cac tinh nang nay.

## Trien khai bang GitHub Pages

1. Tai cac file va thu muc cua du an len repository GitHub.
2. Dam bao `index.html`, `manifest.webmanifest`, `sw.js` va thu muc `icons` nam o thu muc goc.
3. Mo **Settings → Pages**.
4. Trong **Build and deployment**, chon **Deploy from a branch**.
5. Chon nhanh `main` va thu muc `/(root)`.
6. Nhan **Save** va doi GitHub Pages trien khai website.
7. Mo dia chi HTTPS duoc GitHub Pages cung cap.

## Cai dat tren dien thoai

### iPhone

1. Mo dia chi website HTTPS bang Safari.
2. Nhan nut **Chia se**.
3. Chon **Them vao man hinh chinh**.
4. Xac nhan them.

### Android

1. Mo dia chi website HTTPS bang Chrome.
2. Mo menu ba cham.
3. Chon **Cai dat ung dung** hoac **Them vao man hinh chinh**.
4. Xac nhan neu duoc yeu cau.

## Xuat file DXF

1. Nhap thong so can thiet.
2. Kiem tra ban ve trong vung xem truoc.
3. Nhan nut tai DXF.
4. Mo file DXF bang AutoCAD hoac phan mem CAD tuong thich.

Truoc khi su dung cho thi cong hoac san xuat, hay kiem tra kich thuoc, ty le, duong ve va cac thong so trong phan mem CAD.

## Luu y

- Nen truy cap website qua HTTPS de su dung cac tinh nang PWA.
- Neu thay doi file sau khi da trien khai, trinh duyet co the giu cache cu; hay tai lai trang hoac xoa cache neu can.
- DXF dau ra can duoc kiem tra trong phan mem CAD truoc khi su dung chinh thuc.
- Cong cu ho tro thiet ke; nguoi dung can tu xac nhan thong so va ban ve dau ra.

