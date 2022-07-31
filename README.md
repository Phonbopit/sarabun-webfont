TH Sarabun PSK
===

ออกแบบโดย คุณศุภกิจ เฉลิมลาภ

> Update: เนื่องจากผมดาวน์โหลด font มาใช้ เพื่อทำ custom font ผ่าน CSS ใช้งานบนเว็บไซต์ ตัวลิขสิทธิ์ font เป็นของผู้ออกแบบนะครับ และปัจจุบัน ตัว Font ก็ไปอยู่ใน Google Fonts แล้ว ทำให้ใช้งานได้สะดวกว่าเดิมมาก ไม่จำเป็นต้องไปหาดาวน์โหลด font และกำหนด font face เองแล้ว

## การใช้งาน

#### ผ่าน Google Fonts

- Font Sarabun - Google Fonts ได้เลยครับ https://fonts.google.com/specimen/Sarabun

```html
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Sarabun&display=swap" rel="stylesheet">
```

```css
font-family: 'Sarabun', sans-serif;
```

#### แบบ CSS Font face.

```css
@font-face {
    font-family: 'THSarabunNew';
    src: url('thsarabunnew-webfont.eot');
    src: url('thsarabunnew-webfont.eot?#iefix') format('embedded-opentype'),
         url('thsarabunnew-webfont.woff') format('woff'),
         url('thsarabunnew-webfont.ttf') format('truetype');
    font-weight: normal;
    font-style: normal;

}

@font-face {
    font-family: 'THSarabunNew';
    src: url('thsarabunnew_bolditalic-webfont.eot');
    src: url('thsarabunnew_bolditalic-webfont.eot?#iefix') format('embedded-opentype'),
         url('thsarabunnew_bolditalic-webfont.woff') format('woff'),
         url('thsarabunnew_bolditalic-webfont.ttf') format('truetype');
    font-weight: bold;
    font-style: italic;

}

@font-face {
    font-family: 'THSarabunNew';
    src: url('thsarabunnew_italic-webfont.eot');
    src: url('thsarabunnew_italic-webfont.eot?#iefix') format('embedded-opentype'),
         url('thsarabunnew_italic-webfont.woff') format('woff'),
         url('thsarabunnew_italic-webfont.ttf') format('truetype');
    font-weight: normal;
    font-style: italic;

}

@font-face {
    font-family: 'THSarabunNew';
    src: url('thsarabunnew_bold-webfont.eot');
    src: url('thsarabunnew_bold-webfont.eot?#iefix') format('embedded-opentype'),
         url('thsarabunnew_bold-webfont.woff') format('woff'),
         url('thsarabunnew_bold-webfont.ttf') format('truetype');
    font-weight: bold;
    font-style: normal;

}


body {
	font-family: 'THSarabunNew', sans-serif;
}
```
