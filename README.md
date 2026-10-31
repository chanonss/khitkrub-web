<p align="center">
  <img src="icons/192/khitkrub-192.png" alt="KhitKrub: a gold ค on teal" width="96" height="96">
</p>

# คิดครับ · KhitKrub Web v0.1.0

**โปรแกรมตารางคำนวณภาษาไทยและภาษาอังกฤษ ใช้งานฟรีบนเว็บ**

**A free browser-based spreadsheet app for Thai and English.**

**[เปิดใช้งาน / Open KhitKrub](https://khitkrub.app/)** · [KrubOffice](https://kruboffice.app/) · [เขียนครับ · KhianKrub](https://khiankrub.app/) · [พูดครับ · PhutKrub](https://phutkrub.app/)

<p align="center">
  <img src="images/khitkrub-editor.png" alt="KhitKrub with Thai menus: the teal band, the white active tab joined to the ribbon, and the Thai sample workbook ยอดขายร้านกาแฟ, a coffee shop's sales in baht, with a data bar, a colour scale and a chart" width="100%">
</p>

## ประกาศภาษาไทย

**คิดครับบนเว็บ (KhitKrub Web) v0.1.0** เป็นรุ่นแรกครับ เป็นโปรแกรมที่สามในชุด KrubOffice ต่อจากเขียนครับและพูดครับ

- **เมนูภาษาไทย** เปิดครั้งแรกเป็นภาษาไทย สลับเป็นอังกฤษได้ในคลิกเดียวที่ ไฟล์ → ตัวเลือก โปรแกรมจำภาษาไว้ให้
- **ฟอนต์ไทย** เมนูใช้ Sarabun ส่วนตัวอักษรไทยในเซลล์ใช้ TH Sarabun New ตัวเลขและข้อความอังกฤษในเซลล์ยังใช้ฟอนต์เริ่มต้นของโปรแกรมเหมือนเดิม
- **หน้าตาแบบ KrubOffice** แถบด้านบนสีเขียวอมน้ำเงินตามไอคอน แท็บที่เปิดอยู่เป็นสีขาวต่อกับริบบิ้น ไฮไลต์สีทอง มีธีมสว่างและธีมมืด
- **หน้าเริ่มต้นและฉบับร่างในเบราว์เซอร์** เลือกเวิร์กบุ๊กเปล่าหรือตัวอย่าง แต่ละงานเปิดในแท็บใหม่ โปรแกรมเก็บสำเนางานไว้ในเบราว์เซอร์หลังหยุดแก้ประมาณ 2 วินาที กลับมาทำต่อ ดาวน์โหลดเป็น `.xlsx` หรือทิ้งได้ที่หน้าเริ่มต้น ไม่มีอะไรถูกส่งออกจากเครื่อง
- ที่เหลือคือความสามารถของ GridCraft: สูตรและฟังก์ชันกว่า 500 ตัว แผนภูมิ ตารางสรุปข้อมูล (PivotTable) การจัดรูปแบบตามเงื่อนไข เปิดและบันทึกไฟล์ Excel (`.xlsx`) และ CSV

**ที่ยังไม่เสร็จ** ชื่อฟังก์ชันในสูตรเป็นภาษาอังกฤษ ข้อความบางส่วนยังเป็นภาษาอังกฤษ (เช่น ชื่อไฟล์ตัวอย่างและเนื้อหาในตัวอย่าง) และยังไม่มีเลขไทย วันที่แบบ พ.ศ. หรือการอ่านจำนวนเงินเป็นตัวอักษร ยังไม่ได้ทดสอบบน iPad และโทรศัพท์มือถือ

## English announcement

**KhitKrub Web v0.1.0** is the first release: the third app in the KrubOffice suite, after KhianKrub and PhutKrub.

- **Thai menus.** The first visit opens in Thai; File → Options switches to English in one click, and the app remembers it.
- **Thai fonts.** Menus use Sarabun, and Thai letters in cells use TH Sarabun New. Latin text and numbers in cells keep the app's usual default font.
- **A KrubOffice look.** A teal top band in the icon's colour, a white active tab that joins the ribbon, gold highlights, and light and dark themes.
- **A start screen with drafts in the browser.** Pick a blank workbook or a sample; each opens in a new tab. The app keeps a copy of your work in the browser about two seconds after you stop editing; on the start screen you can keep working, download an `.xlsx`, or discard it. Nothing leaves your device.
- Everything else is GridCraft: 500+ worksheet functions, charts, pivot tables, conditional formatting, and opening and saving Excel (`.xlsx`) and CSV files.

**Not done yet:** function names in formulas are English; some text is still English (such as the sample workbooks' own content); there are no Thai digits, Buddhist-era dates or baht-in-words yet; it has not been tested on iPads and phones.

## หน้าตาโปรแกรม / A look around

<table>
<tr>
<td width="50%" valign="top"><img src="images/khitkrub-start.png" alt="The KhitKrub start screen in Thai: a top bar with เปิดไฟล์, ตัวเลือก and the app switcher, the greeting สวัสดีครับ วันนี้จะทำงานอะไรดี, the new-workbook tiles, and drafts kept in this browser" width="100%"><p align="center"><sub><b>หน้าเริ่มต้น / Start screen.</b> เวิร์กบุ๊กเปล่า ตัวอย่าง และฉบับร่างในเบราว์เซอร์ / A blank workbook, samples, and drafts kept in this browser.</sub></p></td>
<td width="50%" valign="top"><img src="images/khitkrub-dark.png" alt="KhitKrub in the dark theme with a deep teal band" width="100%"><p align="center"><sub><b>ธีมมืด / Dark theme.</b> ตารางยังขาวเหมือนตอนพิมพ์ / The sheet stays white, as it will print.</sub></p></td>
</tr>
</table>

## ความสามารถ / Features

| ภาษาไทย | English |
|---|---|
| สูตรและฟังก์ชันกว่า 500 ตัว อาร์เรย์แบบไดนามิก LET และ LAMBDA | 500+ functions, dynamic arrays, LET and LAMBDA |
| แผนภูมิ ตารางสรุปข้อมูล สปาร์กไลน์ และการจัดรูปแบบตามเงื่อนไข | Charts, pivot tables, sparklines and conditional formatting |
| เปิดและบันทึกไฟล์ Excel (`.xlsx`) และ CSV | Open and save Excel files (`.xlsx`) and CSV |
| เมนูภาษาไทยและภาษาอังกฤษ เปิดครั้งแรกเป็นภาษาไทย บางส่วนยังเป็นภาษาอังกฤษ | Thai and English menus; the first visit opens in Thai; some text is still English |
| เมนูใช้ Sarabun ตัวอักษรไทยในเซลล์ใช้ TH Sarabun New | Menus use Sarabun; Thai letters in cells use TH Sarabun New |
| หน้าเริ่มต้นพร้อมฉบับร่างในเบราว์เซอร์ ให้เขียนต่อ ดาวน์โหลด หรือทิ้ง | A start screen with the drafts kept in this browser, to keep working, download or discard |
| ธีมสว่างและธีมมืด | Light and dark themes |

## เริ่มใช้งาน / Getting started

1. เปิด / Visit **[khitkrub.app](https://khitkrub.app/)** บนคอมพิวเตอร์ / on a computer.
2. ที่หน้าเริ่มต้น เลือกเวิร์กบุ๊กเปล่า ตัวอย่าง หรือฉบับร่าง หรือกด **เปิดไฟล์** / On the start screen, pick a blank workbook, a sample or a draft, or press **Open file**.
3. บันทึกงานผ่าน **ไฟล์ → บันทึก** แล้วเก็บไฟล์ไว้ในเครื่อง / Save through **File → Save** and keep the file on your device.

## ที่มา / Credits

KhitKrub is Chanon Sarasuk's Thai adaptation of [GridCraft](https://github.com/storytold/gridcraft) by the ArtCraft team (MIT or Apache-2.0, at your option), one of the apps in [KrubOffice](https://kruboffice.app/). It is not an ArtCraft product and is not affiliated with Microsoft. The screenshots are taken from the running app and show its built-in sample workbooks (original content). This repository holds the compiled site only; the source code is private. Third-party components keep their own licences: see `ATTRIBUTION.md`, `NOTICE`, and `fonts/` (Sarabun: SIL OFL 1.1; TH Sarabun New: GPL with the font exception).

Prepared from version **0.1.0**, source commit `51d0bfaa`.
