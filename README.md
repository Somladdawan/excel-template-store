# ส่งข้อมูลให้พี่หน่อย — Excel Template Store

Mobile-first static storefront for Excel and Google Sheets templates.

## Products
- บันทึกขาด ลา มาสาย — ฿129
- ติดตามโปรเจกต์ — ฿89
- ใบสั่งซื้อ (Purchase Order / PO) — ฿119

## Checkout
Cart calculates totals. Customer opens shop's payment QR via Google Drive, then sends a payment slip and order details via LINE @453oaian. **No automated payment verification or file delivery.**

## Deployment
GitHub > Settings > Pages > Build and deployment > Deploy from a branch > main / (root) > Save.

## Note
The product video and payment QR links are in Google Drive; sharing permissions may need to be changed for public visitors. Do not make paid source files public.


## PO Demo
- Screenshot from Drive folder 3: `assets/product-po.png`
- Original 6.14 MB MP4 `ตัวอย่างการใช้งาน.mp4` is served as 8 ordered binary chunks in `assets/po-demo/` and reassembled in the browser only when playing the preview; this avoids access restrictions to private Drive media and stays below the GitHub upload payload limit.
- Customers must submit their payment slip and email address via LINE. Website does not receive uploads or collect emails.
