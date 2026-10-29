---
name: Landing page TikTok Shop Hải Phòng 05/11/2026
description: Một tờ sticker die-cut ánh kim; giữ chỗ là bóc tem.
colors:
  white: "#FFFFFF"
  navy: "#080F2C"
  navy-deep: "#050A1F"
  cyan: "#13DDE6"
  cyan-soft: "#BFF6F9"
  pink: "#FE2C55"
  desk: "#EEF2FC"
  ink: "#1B2447"
  ink-2: "#47517A"
  on-navy: "#DCE3FA"
  draft-tag: "#FFD84A"
  error: "#A4102F"
  field-fill: "#F6F8FE"
  field-edge: "#C9D3EE"
typography:
  display:
    fontFamily: "'Bricolage Grotesque', 'Be Vietnam Pro', system-ui, sans-serif"
    fontSize: "clamp(1.9rem, 5vw, 4.4rem)"
    fontWeight: 800
    lineHeight: 1
    letterSpacing: "-0.02em"
  headline:
    fontFamily: "'Bricolage Grotesque', 'Be Vietnam Pro', system-ui, sans-serif"
    fontSize: "clamp(1.7rem, 3.8vw, 3rem)"
    fontWeight: 800
    lineHeight: 1.2
    letterSpacing: "-0.02em"
  title:
    fontFamily: "'Bricolage Grotesque', 'Be Vietnam Pro', system-ui, sans-serif"
    fontSize: "clamp(1.1rem, 1.8vw, 1.4rem)"
    fontWeight: 800
    lineHeight: 1.2
    letterSpacing: "-0.02em"
  numeral:
    fontFamily: "'Bricolage Grotesque', 'Be Vietnam Pro', system-ui, sans-serif"
    fontSize: "clamp(2.6rem, 7vw, 5.2rem)"
    fontWeight: 800
    lineHeight: 1
  button:
    fontFamily: "'Bricolage Grotesque', 'Be Vietnam Pro', system-ui, sans-serif"
    fontSize: "clamp(0.95rem, 1.3vw, 1.1rem)"
    fontWeight: 800
    lineHeight: 1.15
    letterSpacing: "0.005em"
  body:
    fontFamily: "'Be Vietnam Pro', system-ui, -apple-system, 'Segoe UI', sans-serif"
    fontSize: "1.0625rem"
    fontWeight: 400
    lineHeight: 1.65
  label:
    fontFamily: "'Be Vietnam Pro', system-ui, -apple-system, 'Segoe UI', sans-serif"
    fontSize: "0.95rem"
    fontWeight: 700
    lineHeight: 1.3
rounded:
  tag: "6px"
  field: "14px"
  button: "18px"
  header: "20px"
  sticker: "22px"
  photo: "26px"
  sheet: "30px"
  frame: "34px"
spacing:
  ring: "7px"
  ring-button: "6px"
  gutter: "clamp(1rem, 4vw, 2.5rem)"
  section-y: "clamp(3.5rem, 8vw, 6.5rem)"
  grid-gap: "2.5rem"
  wrap: "1240px"
components:
  button-register:
    backgroundColor: "{colors.pink}"
    textColor: "{colors.navy}"
    typography: "{typography.button}"
    rounded: "{rounded.button}"
    padding: "1.05em 1.6em"
  button-quiet:
    backgroundColor: "{colors.white}"
    textColor: "{colors.navy}"
    typography: "{typography.label}"
    rounded: "{rounded.field}"
    padding: "0.8rem 1.2rem"
  sticker:
    backgroundColor: "{colors.white}"
    textColor: "{colors.ink}"
    typography: "{typography.body}"
    rounded: "{rounded.sticker}"
    padding: "1.4rem 1.5rem"
  sticker-navy:
    backgroundColor: "{colors.navy}"
    textColor: "{colors.on-navy}"
    rounded: "{rounded.sticker}"
  sticker-cyan:
    backgroundColor: "{colors.cyan}"
    textColor: "{colors.navy}"
    rounded: "{rounded.sticker}"
  h1-sticker-white:
    backgroundColor: "{colors.white}"
    textColor: "{colors.navy}"
    typography: "{typography.display}"
  h1-sticker-navy:
    backgroundColor: "{colors.navy}"
    textColor: "{colors.white}"
    typography: "{typography.display}"
  h1-sticker-cyan:
    backgroundColor: "{colors.cyan}"
    textColor: "{colors.navy}"
    typography: "{typography.display}"
  field-input:
    backgroundColor: "{colors.field-fill}"
    textColor: "{colors.ink}"
    rounded: "{rounded.field}"
    padding: "0.85rem 1rem"
  stamp-done:
    backgroundColor: "{colors.cyan}"
    textColor: "{colors.navy}"
    typography: "{typography.headline}"
    rounded: "16px"
    padding: "0.35em 0.7em"
  draft-tag:
    backgroundColor: "{colors.draft-tag}"
    textColor: "{colors.navy}"
    rounded: "{rounded.tag}"
    padding: "0.15rem 0.55rem"
---

# Design System: Landing page TikTok Shop Hải Phòng 05/11/2026

## Overview

**Creative North Star: "Tờ sticker ánh kim"**

Trang là một tờ sticker die-cut ánh kim đặt trên giấy backing lilac nhạt có lưới chấm. Mọi khối nội dung là một nhãn dán viền trắng dày, bo lớn, đổ bóng nổi mềm, xoay lệch 1–4 độ và cỡ không đều. Giữ chỗ là hành động bóc tem: nút đăng ký là nhãn hồng bị bóc một góc, bấm vào thì nhấc lên rồi trang cuộn tới form. Roll seed tham chiếu: `seed:55310a94610d82d1`.

Bố cục cố ý không đều nhưng có trật tự: sticker khác kích thước, khác góc xoay, chồng lệch nhau; không có hàng thẻ bằng nhau và không có hero tách đôi chữ/ảnh theo kiểu mặc định. Nền xen kẽ giữa các dải: lilac chấm (backing), trắng, navy, cyan. Bố cục sticker đó là thứ nhận ra được ngay cả khi bỏ hết chữ. Ánh kim (foil) cyan–lilac–hồng nhạt chỉ xuất hiện ở hai nơi: khung Key Visual và mép form đăng ký.

Hệ thống bám bảng màu "Bright TikTok Commerce" của brief gốc (trắng, navy, cyan, hồng) và giọng thực dụng, B2B của sản phẩm. Hồng là màu hành động, không phải màu trang trí.

**Key Characteristics:**
- Mọi khối nội dung là sticker: nền phẳng, viền trắng 7px, shadow nổi, `rotate(var(--rot))`.
- Hồng `#FE2C55` chỉ tô nền nút đăng ký, chữ trên nút là navy.
- Ánh kim chỉ ở Key Visual và mép form.
- Tiêu đề Bricolage Grotesque 800; thân Be Vietnam Pro.
- Một khoảnh khắc chuyển động được dàn dựng: tiêu đề và Key Visual "dán" vào trang, và nút bóc tem.
- Nhãn vàng `[CẦN CHỐT]` là phần giàn tạm cho nội dung Ban tổ chức chưa duyệt, ẩn khi bỏ `data-draft` ở thẻ body.

## Colors

Palette giới hạn: trắng, navy, cyan là thân hệ thống; hồng chỉ cho hành động; vàng và đỏ chỉ cho trạng thái.

### Primary
- **Navy Mực In** (`#080F2C`, `colors.navy`): màu chữ tiêu đề và chữ trên nút hồng, nền dải navy (S3 case study, S8 đăng ký), nền sticker nhấn mạnh, viền focus, scrollbar, radio/checkbox accent.
- **Cyan Tem Nhãn** (`#13DDE6`, `colors.cyan`): nền dải quyền lợi (S5), nhãn H1 thứ ba, chip, nhãn thời gian nổi bật, điểm mốc timeline, quầng focus (6px), con dấu "ĐÃ GHI NHẬN". Là màu nhấn thứ hai, dùng nhiều hơn hồng.

### Secondary
- **Hồng Bóc Tem** (`#FE2C55`, `colors.pink`): chỉ làm nền của nút đăng ký (nút trong hero, header, các CTA cuối section, nút submit, thanh CTA dính). Chữ trên nút là navy, tương phản đạt AA (5,1:1); chữ trắng trên hồng không đạt.

### Neutral
- **Giấy Backing** (`#EEF2FC`, `colors.desk`): nền trang và dải có chấm; lưới chấm dùng `#D3DCF1` / `#D9E1F4`, ghi trực tiếp trong CSS.
- **Trắng Tem** (`#FFFFFF`, `colors.white`): nền sticker, viền die-cut, header, dải FAQ.
- **Mực Thân Bài** (`#1B2447`, `colors.ink`): chữ thân trên nền sáng.
- **Mực Phụ** (`#47517A`, `colors.ink-2`): chữ phụ, mô tả, gợi ý trên nền sáng.
- **Chữ Trên Navy** (`#DCE3FA`, `colors.on-navy`): chữ thân trên dải navy và footer.
- **Cyan Nhạt** (`#BFF6F9`, `colors.cyan-soft`): hover của nav, FAQ đang mở, tuỳ chọn form đã chọn, sticker lý do số 2.
- **Navy Sâu** (`#050A1F`, `colors.navy-deep`): chỉ nền footer.
- **Nền Ô Nhập** (`#F6F8FE`, `colors.field-fill`) và **Viền Ô Nhập** (`#C9D3EE`, `colors.field-edge`): trường form và tuỳ chọn.

### Status
- **Vàng Nháp** (`#FFD84A`, `colors.draft-tag`): chỉ cho nhãn `[CẦN CHỐT]` và thanh bản nháp. Không dùng cho trang trí.
- **Đỏ Lỗi** (`#A4102F`, `colors.error`): viền ô nhập và thông báo lỗi form.

### Ánh kim (Foil)
`linear-gradient(125deg, #8FF1F6 0%, #DCCBFF 34%, #FFC7DB 58%, #9CF3F7 100%)` (cyan, lilac, hồng nhạt, cyan). Không biểu diễn được là một màu nên nằm trong sidecar `.impeccable/design.json`.

### Named Rules
**The Pink Is An Action Rule.** Hồng chỉ làm nền của nút đăng ký. Không dùng cho tiêu đề, icon, đường kẻ, nền sticker thông tin. Hiếm là điểm mấu chốt: mắt phải tìm thấy nút ngay.

**The Foil Twice Rule.** Ánh kim chỉ ở khung Key Visual và mép form. Thêm lần thứ ba là làm hỏng độ hiếm của nó.

**The Navy On Pink Rule.** Chữ trên nền hồng là navy. Đây là quyết định theo tương phản, không phải sở thích.

## Typography

**Display Font:** Bricolage Grotesque (variable, 700–800; fallback Be Vietnam Pro, system-ui)
**Body Font:** Be Vietnam Pro (400 / 600 / 700; fallback system-ui, -apple-system, Segoe UI)

Cả hai font nhúng base64 woff2, chỉ subset latin và vietnamese để tiếng Việt có dấu hiển thị đúng ở mọi cỡ.

**Character:** Bricolage nặng, hơi dị hình, có giọng tem nhãn và áp phích; Be Vietnam Pro trung tính, dễ đọc cho người đọc nhiều độ tuổi trên điện thoại. Tiêu đề thường viết hoa theo copy gốc của BTC.

### Hierarchy
- **Display** (800, `clamp(1.9rem, 5vw, 4.4rem)`, 1, tracking -0.02em): H1, ba nhãn chồng lệch trong hero.
- **Headline** (800, `clamp(1.7rem, 3.8vw, 3rem)`, 1.2): H2 mỗi section, tối đa khoảng 21ch.
- **Title** (800, `clamp(1.1rem, 1.8vw, 1.4rem)`, 1.2): H3 trong sticker (lý do, nhóm quyền lợi, tên diễn giả, địa điểm). Tiêu đề case study lớn hơn: `clamp(1.6rem, 3.4vw, 2.6rem)`.
- **Numeral** (800, `clamp(2.6rem, 7vw, 5.2rem)`, 1): chỉ "×20" của case Calem.Club; số thứ tự trong vòng tròn, chữ cái nhóm quyền lợi dùng 800 cỡ 0,95–1,2rem.
- **Body** (400, 1.0625rem, 1.65): đoạn văn; độ rộng đọc khoảng 56–68ch.
- **Label** (700, 0.95rem, 1.3): nhãn trường form, nút phụ, chip, tóm tắt "Xem thêm". Nav dùng 600 cỡ 0,82rem.

### Named Rules
**The Heading Weight Rule.** Mọi h1–h4 dùng Bricolage 800, tracking -0.02em, `text-wrap: balance`. Chữ thân không bao giờ dùng Bricolage.

**The Tabular Numbers Rule.** Giờ, ngày, giá, số liệu dùng `font-variant-numeric: tabular-nums`.

## Layout

Khung chứa tối đa 1240px (hero và header rộng tới 1380px), lề ngang `clamp(1rem, 4vw, 2.5rem)`. Section theo nhịp dải: padding dọc `clamp(3.5rem, 8vw, 6.5rem)`, khoảng cách lưới 1,5–2,5rem. Hero là một "tờ" lớn bo 28px có lưới chấm và góc giấy bị bóc ở dưới phải.

Bố cục là lưới không đối xứng: tỉ lệ 5:7 hoặc 7:5 (lý do, case, form, lịch trình), lưới 12 cột cho quyền lợi (7+5, 5+7), hero 1,2fr / 0,85fr. Sticker lệch nhau bằng `translate` nhỏ và `margin-left`. Cột trái của form và khối địa điểm `position: sticky`.

Breakpoint: 900px (mọi lưới về một cột), 480px (ảnh diễn giả xếp trên bio), 1559px (nav ngang thu thành nút Menu, nút CTA header ẩn, thanh CTA dính hiện). Thanh CTA dính chỉ hiện khi đã qua hero và chưa tới form. `scroll-padding-top: 96px` bù header dính.

## Elevation & Depth

Hệ thống lai: nền phẳng, chiều sâu đến từ viền trắng die-cut và shadow nổi mềm có offset dọc, không từ gradient. Shadow chủ đạo `--lift` gồm một đường 2px mờ và một bóng đổ rộng; trong dải navy và footer nó được thay bằng bóng đen trung tính, đậm hơn để còn đọc được trên nền tối.

### Shadow Vocabulary
- **Lift** (`box-shadow: 0 0 0 7px #fff, 0 2px 0 rgba(8,15,44,.07), 0 14px 26px -8px rgba(8,15,44,.28)`): mọi sticker (`.stk`).
- **Lift on navy** (`0 2px 0 rgba(0,0,0,.28), 0 14px 26px -8px rgba(0,0,0,.65)`): thay `--lift` trong dải navy và footer.
- **Peel button** (`0 0 0 6px #fff, 0 14px 22px -8px rgba(8,15,44,.38)`; hover `0 20px 28px -8px rgba(8,15,44,.45)`): nút đăng ký.
- **Key Visual** (`0 0 0 8px #fff, 0 26px 44px -10px rgba(8,15,44,.35)`) và **Form sheet** (`0 0 0 8px #fff, 0 26px 50px -12px rgba(0,0,0,.55)`): hai khung ánh kim.
- **Hero sheet** (`0 18px 50px rgba(8,15,44,.12)`): tờ hero.

### Named Rules
**The Die-Cut Ring Rule.** Mỗi sticker có viền trắng đặc quanh (7px; nút 6px; khung kim 8px) trước khi có bóng. Viền trắng là thứ làm nó thành "nhãn dán"; bóng chỉ nâng nó lên khỏi giấy.

**The Neutral Shadow On Navy Rule.** Trên nền navy dùng bóng đen trung tính, không dùng bóng navy (chìm mất).

## Shapes

Ngôn ngữ hình: bo góc lớn, gần như viên thuốc nhưng vẫn là hình chữ nhật mềm. Thang bo: nhãn nháp 6px, ô nhập và chip 14px, nút 18px, header 20px, sticker 22px (`--r`), khung ảnh diễn giả 26px, tờ hero 28px, form 30px (ruột trong 19px), Key Visual 34px (ảnh trong 24px). Vòng tròn 50% cho số thứ tự, dấu tick, nút mở FAQ.

Silhouette lặp lại: nhãn xoay lệch, góc giấy bị bóc (nút và hero), tem chữ nhật với chấm tròn nối timeline bằng nét đứt cyan, con dấu tròn góc "ĐÃ GHI NHẬN" xoay -8°. Icon là SVG nét 1,9px, bo đầu (tick, mũi tên, lịch, ghim, chevron), không dùng font icon hay emoji.

## Components

### Buttons
- **Shape:** nhãn bóc tem, bo 18px, viền trắng 6px (`.btn-peel`); xoay -1°.
- **Primary (đăng ký):** nền hồng, chữ navy Bricolage 800, padding `1.05em 1.6em`. Một góc dưới phải là mảnh giấy trắng cuộn (20px) làm dấu "đang bị bóc".
- **Hover / Focus:** xoay -2° và nhấc 3px; góc bóc to ra thành 38px. Khi bấm: thêm lớp nhấc (xoay -4°, nhấc 10px, phóng 1,04) trong 200ms rồi cuộn mượt tới form và chuyển focus (bàn phím vào ô tên, chuột/chạm vào H2). Khi `prefers-reduced-motion`, cuộn thẳng không hiệu ứng.
- **Disabled:** độ mờ 0,65, con trỏ progress khi đang gửi.
- **Quiet (`.btn-quiet`):** nền trắng, chữ navy, bo 14px, viền 5px, cho hành động phụ như "Xem đường đi trên Google Maps". Hover nhấc 2px, xoay -1°.

### Stickers (Cards / Containers)
- **Corner Style:** 22px; nền trắng mặc định, biến thể navy (nhấn mạnh), cyan (số liệu, chip) và cyan-soft.
- **Shadow Strategy:** Lift (xem Elevation).
- **Rotation:** biến `--rot` từ -3,5° đến 1,8°, mỗi sticker khác nhau; cỡ cũng khác nhau (có sticker chiếm cả hàng, có sticker thụt `margin-left`).
- **Internal Padding:** khoảng 1,2–1,8rem.

### Hero H1 (ba nhãn chồng lệch)
Ba `span` trong H1: "BỨT PHÁ DOANH SỐ" nền trắng xoay -2°, "MÙA MUA SẮM" nền navy chữ trắng xoay 1,4° thụt vào, "CUỐI NĂM CÙNG TIKTOK SHOP!" nền cyan nhỏ hơn xoay -1°.

### Key Visual
Ảnh vuông 800x800 trong khung ánh kim 12px, bo 34px, nghiêng 3°, viền trắng 8px; trên màn lớn, ba sticker thông tin (ngày giờ, địa điểm, miễn phí; trắng, navy, cyan) đè lên mép dưới khung.

### Navigation
Header dính là một viên nhãn trắng: logo đối tác trái, liên kết nav 600 cỡ 0,82rem, hover nền cyan-soft, nút CTA cuối. Từ 1559px trở xuống, nav thu thành nút "Menu" navy mở ngăn xổ nhãn trắng (có CTA); thanh CTA dính hiện ở đáy màn hình (ngày + "Đăng ký ngay").

### Timeline giai đoạn (`.phase`)
Danh sách các sticker xoay nhẹ, lệch trái luân phiên, nối bằng đường đứng nét đứt cyan 4px có chấm cyan (viền navy) ở mỗi mốc. Dùng cho 4 pha của case Bonami.

### Lịch trình (`.roll`)
Cuộn băng các hàng trắng bo 16px xoay ±0,35°, mỗi hàng có nhãn giờ navy; hai buổi Training đổi nền cyan. Cạnh nó là sticker địa điểm dính (sticky).

### FAQ
Mỗi câu hỏi là sticker `details` xoay ±0,3°, bo 18px; nút mở là vòng tròn navy có chevron, khi mở chuyển cyan, nền sticker thành cyan-soft.

### Inputs / Fields
- **Style:** nền `field-fill`, viền 2px `field-edge`, bo 14px, padding `0.85rem 1rem`, cỡ chữ 1,02rem. Tuỳ chọn radio/checkbox là hàng bo 12px; hàng đã chọn đổi cyan-soft và viền navy.
- **Focus:** viền navy, nền trắng, quầng cyan 4px. Focus toàn trang: viền navy 3px, offset 3px, quầng cyan 6px.
- **Error:** viền `error`, thông báo `error` 600 0,9rem ngay dưới trường; hộp lỗi tổng nền hồng nhạt chữ `error`.

### Form sheet (tờ ánh kim)
Ruột trắng bo 19px trong viền ánh kim 12px, bo 30px, xoay 0,6°, viền trắng ngoài 8px. Nút submit là nút đăng ký bề ngang đầy đủ. Thành công: form ẩn, hiện con dấu "ĐÃ GHI NHẬN" (nền cyan, viền navy 5px, xoay -8°, đập xuống).

### Nhãn nháp (`.tbd`)
Nhãn vàng xoay -1°, bo 6px, chữ navy 700, đánh dấu mọi nội dung chưa chốt; thanh `draftbar` ở đầu trang. Cả hai bị ẩn khi thẻ body không có `data-draft`. Đây là giàn tạm của bản nháp, không phải thành phần lâu dài của hệ thống.

### Motion
Một khoảnh khắc được dàn dựng: lúc tải trang, ba nhãn H1, Key Visual và ba sticker thông tin "dán" vào (`slap`, 0,7s, rơi từ trên xuống 22px và thu từ 1,07, lệch nhịp 0,12–0,5s) cùng nút bóc tem. Easing chung `cubic-bezier(.16, 1, .3, 1)`. Các phản hồi nhỏ: chevron xoay, thanh CTA dính trượt lên (0,45s), con dấu "ĐÃ GHI NHẬN" đập xuống (0,55s). Tất cả tôn trọng `prefers-reduced-motion`: không có animation keyframe, transition rút còn 0,01ms, cuộn không mượt.

## Do's and Don'ts

### Do:
- **Do** dùng hồng `#FE2C55` chỉ làm nền nút đăng ký, chữ navy `#080F2C` (5,1:1).
- **Do** làm mọi khối nội dung thành sticker: viền trắng 7px, bo 22px, `--lift`, xoay lệch 1–4°.
- **Do** để các sticker khác cỡ, khác góc xoay, chồng lệch hoặc thụt so le.
- **Do** giữ ánh kim chỉ ở khung Key Visual và mép form.
- **Do** dùng bóng đen trung tính trong dải navy và footer.
- **Do** giữ tiêu đề ở Bricolage Grotesque 800, thân ở Be Vietnam Pro, giữ subset Vietnamese.
- **Do** để điều kiện quyền lợi và disclaimer hiển thị ở cỡ chữ đọc được, ngang hàng với quyền lợi.
- **Do** dùng nhãn vàng `[CẦN CHỐT]` cho mọi nội dung chưa duyệt, và ẩn chúng bằng `data-draft`.
- **Do** giữ vùng chạm đủ lớn: tóm tắt "Xem thêm" cao tối thiểu 44px, nút CTA có padding trên 1em.

### Don't:
- **Don't** tô hồng tiêu đề, icon, đường kẻ hoặc sticker thông tin.
- **Don't** đặt chữ trắng lên nền hồng.
- **Don't** dùng gradient trên chữ.
- **Don't** dùng emoji; icon là SVG nét.
- **Don't** đặt nhãn nhỏ (eyebrow) phía trên tiêu đề section.
- **Don't** xếp hàng thẻ bằng nhau, bằng cỡ, thẳng hàng.
- **Don't** dùng bóng navy trên nền navy.
- **Don't** thêm nhiều khoảnh khắc chuyển động cạnh tranh với màn "dán" hero và nút bóc tem.
- **Don't** dùng vàng `#FFD84A` ngoài nhãn nháp.
- **Don't** thêm countdown, số vé còn lại hoặc số liệu chưa có nguồn.

## Raster Provenance

Mọi ảnh bitmap trên trang là cắt hoặc nén lại từ các file gốc do Ban tổ chức cung cấp, đặt cạnh trang trong thư mục dự án. Không có ảnh nào do mô hình tạo ảnh sinh ra.

| Ảnh trên trang | File gốc | Xử lý |
| --- | --- | --- |
| Key Visual ở hero | `Ảnh sự kiện.jpg` (2000x2000) | Thu nhỏ còn 1080x1080, JPEG chất lượng 82 |
| Dải logo header và footer (Sở Công Thương, TikTok Shop, TikTok for Business Starter Lab, Meta Ecom, MARS Marketing) | Dải trên cùng của `Ảnh sự kiện.jpg` | Cắt, nâng nền pastel lên trắng, rộng 1500px |
| Ms. Trần Thị Hồng Vân | `Diễn giả Hồng Vân.JPG` (4000x6000) | Cắt tỉ lệ 4:5 theo khuôn mặt, thu còn 480x600 |
| Mr. Phạm Minh Hảo | `Diễn giả Minh Hảo.jpg` (1888x2560) | Cắt 4:5, thu còn 480x600 |
| Ms. Nguyễn Quỳnh Hương | `Diễn giả Quỳnh Hương.JPG` (1230x1279) | Cắt 4:5, thu còn 480x600 |
| Noah Nguyễn | `Diễn giả Noah Nguyễn.jpg` (822x1080) | Cắt 4:5, thu còn 480x600 |
| Logo Bonami (Case Study 01) | `BONAMI.webp` (1200x1200) | Cắt cụm logo đám mây góc trên trái `(88, 92, 312, 240)`, phóng 2× còn 448x296 |
| Logo Calem.Club (Case Study 02) | `CALEM.CLUB.jpeg` (447x447) | Cắt sát vùng biểu tượng và chữ còn 434x314 |

Tất cả nhúng base64 trong `index.html`, không có file ảnh riêng đi kèm. Ảnh Noah là file nhỏ nhất (822x1080, khoảng 38 KB), đủ nét ở khung hiển thị hiện tại nhưng không nên phóng to hơn.

Lưới chấm, góc giấy bóc và ánh kim là CSS thuần, không phải ảnh.

## Known Deviations

Ghi lại trung thực những chỗ bản build lệch khỏi phác thảo hoặc chưa đạt ý đồ; đây không phải quy tắc cho màn hình sau.

- **H2 màu navy, không hồng.** Phác thảo đã chọn có sticker H2 màu hồng; bản build theo bản nâng cấp đã duyệt (hồng chỉ dành cho hành động) nên H2 dùng navy.
- **Chữ nút là navy, không trắng.** Chữ trắng trên `#FE2C55` không đạt AA; navy trên hồng đạt 5,1:1.
- **Ánh kim không có ở mép CTA.** Hợp đồng hướng đi ban đầu nói ánh kim ở "khung Key Visual và mép CTA"; bản build đặt nó ở khung Key Visual và mép form, nút CTA chỉ có viền trắng và góc bóc.
- **Các section giữa trang diễn đạt thế giới sticker yếu hơn.** S2 (vì sao), S5 (quyền lợi), S6 (chi tiết) và S7 (FAQ) chủ yếu là sticker xoay nhẹ trên lưới, ít tính "tờ tem" hơn hero, S3 và form. Lưới diễn giả 2x2 và hàng bước 5 ô vẫn khá đều.
- **Không đưa vào hệ thống:** lớp `.case-tag` (nhãn nhỏ phía trên tiêu đề case, có trong CSS nhưng không dùng trong HTML, và là kiểu eyebrow); `--pink-d` và `--navy-2` (khai báo nhưng không dùng); `caret-color` hồng của ô nhập (rò rỉ nhỏ của hồng ra ngoài nút đăng ký); trọng lượng 500 và 800 của Be Vietnam Pro (`.fact small`, `.ast`) không có file tương ứng nên trình duyệt dùng 400 và 700.
