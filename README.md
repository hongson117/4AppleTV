<div align="center">
  <img src="docs/icon.png" alt="4AppleTV Logo" width="160" style="border-radius: 36px; box-shadow: 0 12px 32px rgba(10,132,255,0.35);" />
  <h1>4AppleTV</h1>
  <p><strong>Trung tâm Điều khiển Apple TV Toàn diện & Cài đặt Ứng dụng (.IPA) Không dây từ iPhone / iPad</strong></p>

  <p>
    <a href="https://github.com/hongson117/4AppleTV/releases/latest/download/4AppleTV.ipa">
      <img src="https://img.shields.io/badge/Tải_Về_Ngay-4AppleTV.ipa-0A84FF?style=for-the-badge&logo=apple&logoColor=white" alt="Tải về 4AppleTV.ipa" />
    </a>
    <a href="https://github.com/hongson117/4AppleTV/releases/latest">
      <img src="https://img.shields.io/github/v/release/hongson117/4AppleTV?style=for-the-badge&label=Phiên_bản_Mới_nhất&color=30D158" alt="Phiên bản mới nhất" />
    </a>
    <img src="https://img.shields.io/badge/iOS_%2F_iPadOS-17.0%2B-5E5CE6?style=for-the-badge" alt="iOS 17.0+" />
    <img src="https://img.shields.io/badge/tvOS-15.0%2B-1C1C1E?style=for-the-badge&logo=appletv" alt="tvOS 15.0+" />
  </p>
</div>

---

## 🌟 1. Giới Thiệu & Miêu Tả Chi Tiết Sản Phẩm (Overview)

**4AppleTV** là ứng dụng chuyên dụng thế hệ mới dành cho người dùng **Apple TV HD / Apple TV 4K** trên nền tảng **iPhone và iPad (iOS/iPadOS 17.0+)**. Được thiết kế với kiến trúc lõi **Rust (`libtvs_core`)** kết hợp giao diện **SwiftUI Native Đa ngôn ngữ (`Theo hệ thống / Tiếng Việt / English`)**, **4AppleTV** hợp nhất hoàn hảo hai nhu cầu quan trọng nhất của người dùng Apple TV vào một ứng dụng duy nhất:

1. **Điều khiển từ xa (Smart Remote) & Mở nhanh ứng dụng trên Apple TV** với độ trễ cực thấp qua giao thức Apple Companion Link chính gốc.
2. **Cài đặt ứng dụng bên thứ ba (`.ipa` Sideloading) không dây qua mạng Wi-Fi** trực tiếp từ iPhone lên Apple TV **mà không cần máy tính Mac, không cần Xcode và không cần dây cáp USB-C**.

> 🇬🇧 **English Summary**: **4AppleTV** (v1.1.0+) natively supports **English**, **Vietnamese**, and **System Default** languages (switchable live in-app via the 🌐 globe button or **Settings ▸ Language**). It combines an ultra-low-latency Apple TV Remote + 1-tap TV App Launcher with a PC-free wireless tvOS `.ipa` sideloader (supporting both free Apple IDs and `.p12` + `.mobileprovision` certificates). For Sideload Pass licenses or support, contact **[hongson1812@gmail.com](mailto:hongson1812@gmail.com)**.

---

### 🔥 Các Tính Năng Đột Phá Của 4AppleTV

#### 🎮 1. Điều Khiển Apple TV Toàn Diện (Tab **Điều khiển**)
* **Hai chế độ điều khiển linh hoạt**: Chuyển đổi tức thì giữa **Bề mặt cảm ứng vuốt (Touchpad)** mượt như Siri Remote thật và **Cụm phím điều hướng 5 chiều (D-Pad)** chính xác từng nhịp bấm.
* **Tùy chỉnh độ nhạy Touchpad**: Điều chỉnh độ nhạy vuốt từ `0.4x` đến `2.2x` phù hợp với thói quen sử dụng của từng người.
* **Đầy đủ phím chức năng phần cứng**: Nguồn (Bật/Tắt TV), Tắt tiếng (Mute), Tăng/Giảm âm lượng, Quay lại (Back/Menu), Màn hình chính (TV/Home), Phát/Tạm dừng (Play/Pause), Tua lùi 10s, Tua tới 10s.
* **Bàn phím Tiếng Việt có dấu tức thì**: Nhập văn bản tìm kiếm phim, YouTube, mật khẩu Wi-Fi hoặc tài khoản trên Apple TV ngay từ bàn phím iPhone với hỗ trợ đầy đủ Tiếng Việt Unicode.
* **Phản hồi xúc giác (Haptic Feedback)**: Từng thao tác chạm và điều hướng đều có phản hồi rung tinh tế giúp điều khiển không cần nhìn màn hình điện thoại.

#### 🚀 2. Lưới Ứng Dụng TV & Mở Nhanh 1 Chạm (Tab **Ứng dụng**)
* **Hiển thị trực quan toàn bộ ứng dụng trên Apple TV**: Tự động đồng bộ danh sách các ứng dụng đã cài qua 4AppleTV và các ứng dụng phổ biến tại Việt Nam (*VPhimTV, AceSport TV, FPT Play, TV360, Infuse, LiveContainerTV, MultiTVOS, YouTube, Netflix...*).
* **Mở ứng dụng tức thì (1-Tap Launch)**: Chạm vào biểu tượng ứng dụng trên iPhone để mở ngay ứng dụng đó trên màn hình Apple TV mà không cần tìm kiếm trên màn hình TV.
* **Tự động chuyển sang Remote**: Sau khi bấm mở ứng dụng trên TV, 4AppleTV tự động đưa bạn về màn hình **Điều khiển** để thao tác ngay lập tức.

#### 📦 3. Cài Đặt `.IPA` Không Dây Lên Apple TV (Tab **Cài app**)
* **Hoàn toàn không cần máy tính (PC-Free / Mac-Free)**: Chọn bất kỳ file `.ipa` dành cho tvOS ngay trong ứng dụng **Tệp (Files)** trên iPhone và bắn trực tiếp sang Apple TV qua Wi-Fi nội bộ.
* **Tự động lấy UDID & Ghép đôi Thiết bị**: Không cần cắm cáp vào máy Mac để lấy UDID — 4AppleTV tự động đọc UDID, kiểu máy (Apple TV 4K Gen 1/2/3, Apple TV HD) và phiên bản tvOS qua mạng LAN.
* **Hỗ trợ cả 2 phương thức ký ứng dụng**:
  1. **Tài khoản Apple ID miễn phí (Free Developer Account)**: Tự động đăng ký thiết bị, tạo chứng chỉ phát triển, cấp Provisioning Profile và ký `.ipa` ngay trên iPhone.
  2. **Chứng chỉ mua ngoài (`.p12` + `.mobileprovision`)**: Dành cho người dùng có chứng chỉ năm (1 năm không hết hạn 7 ngày, cài không giới hạn số lượng ứng dụng). Chỉ cần nhập file `.p12`, mật khẩu và file `.mobileprovision` dành cho tvOS để ký và cài đặt siêu tốc.

#### 🔄 4. Tự Động Làm Mới Chứng Chỉ 7 Ngày (Auto-Refresh)
* Với người dùng sử dụng **Apple ID miễn phí** (chứng chỉ có hạn 7 ngày), 4AppleTV theo dõi thời hạn từng ứng dụng theo thời gian thực và hỗ trợ **Tự động làm mới (Refresh) hàng ngày** khi iPhone và Apple TV cùng kết nối Wi-Fi, giữ cho ứng dụng trên TV luôn hoạt động liên tục.

#### 🔄 5. Chế Độ Tự Động Cập Nhật Ứng Dụng (In-App Auto-Update)
* **Kiểm tra phiên bản mới tự động**: Mỗi khi mở ứng dụng (hoặc bấm **Kiểm tra cập nhật ngay** trong phần Cài đặt), 4AppleTV tự động kiểm tra bản dựng mới nhất từ kho phát hành chính thức.
* **Tải & Cài đè `.ipa` ngay trong ứng dụng**: Khi có bản cập nhật mới, bạn chỉ cần bấm **"Tải .IPA & Mở trong App Ký"** — ứng dụng sẽ tải gói `4AppleTV.ipa` mới nhất về máy và mở bảng Chia sẻ (Share Sheet) để bạn chuyển thẳng sang *Feather, ESign, SideStore, AltStore, TrollStore* cập nhật đè mà không mất dữ liệu hay mã bản quyền.

#### 🌐 6. Đa Ngôn Ngữ Thông Minh (System / Tiếng Việt / English)
* **Tự động theo ngôn ngữ máy hoặc chuyển trực tiếp 1 chạm**: 4AppleTV tự động nhận diện ngôn ngữ hệ thống iOS/iPadOS ngay lần đầu mở máy và cho phép đổi tức thì giữa **Theo hệ thống**, **Tiếng Việt** và **English** ngay tại nút 🌐 hoặc **Cài đặt ▸ Ngôn ngữ** mà không cần khởi động lại ứng dụng.

#### 🛡️ 7. Bảo Mật Cấp Độ Cao, Chống Sao Chép BLA & Chẩn Đoán Minh Bạch
* **Mọi thông tin nhạy cảm nằm trên thiết bị của bạn**: Mật khẩu Apple ID, khóa ghép đôi (Pairing Key) và chứng chỉ `.p12` được mã hóa và lưu trữ độc quyền trong **iOS Keychain** trên iPhone của bạn.
* **Bảo vệ chống sao chép & dịch ngược tự động (BLA Counter-REA Shield)**: Nhân nhị phân `arm64` và gói Bundle được gia cố đa lớp, gắn kết mật mã định danh chính chủ của **4AppleTV** và kênh hỗ trợ chính thức **`hongson1812@gmail.com`**, đồng thời tương thích tuyệt đối với mọi công cụ ký iOS (*Feather, ESign, SideStore, AltStore, TrollStore, Sideloadly*).
* **Nhật ký chẩn đoán thông minh (Redacted Diagnostics)**: Tự động ẩn toàn bộ thông tin nhạy cảm (PIN, mật khẩu, token) khi xuất log kiểm tra lỗi kết nối.

---

## 📥 2. Tải Về & Nguồn Cài Đặt Chính Thức

| Hạng mục | Liên kết trực tiếp |
| :--- | :--- |
| **Gói cài đặt iOS/iPadOS (`.ipa`)** | [**⬇️ Tải xuống `4AppleTV.ipa` (Bản mới nhất)**](https://github.com/hongson117/4AppleTV/releases/latest/download/4AppleTV.ipa) |
| **Trang Releases (Lịch sử phiên bản)** | [https://github.com/hongson117/4AppleTV/releases](https://github.com/hongson117/4AppleTV/releases) |
| **Nguồn Repo (AltStore / SideStore / Feather / ESign)** | `https://raw.githubusercontent.com/hongson117/4AppleTV/main/source.json` |
| **Feed Kiểm tra Cập nhật Tự động (`version.json`)** | `https://raw.githubusercontent.com/hongson117/4AppleTV/main/version.json` |

### Cách thêm nhanh nguồn Repo vào Feather / ESign / SideStore / AltStore:
Sao chép đường dẫn dưới đây và dán vào mục **Sources / Kho nguồn** trong ứng dụng ký của bạn để nhận cập nhật tự động:
```text
https://raw.githubusercontent.com/hongson117/4AppleTV/main/source.json
```

---

## 📖 3. Hướng Dẫn Sử Dụng Chi Tiết Từ A – Z

### Bước 1: Cài đặt `4AppleTV.ipa` lên iPhone hoặc iPad
Bạn có thể cài đặt file [`4AppleTV.ipa`](https://github.com/hongson117/4AppleTV/releases/latest/download/4AppleTV.ipa) lên iPhone/iPad (chạy iOS/iPadOS 17.0 trở lên) bằng bất kỳ công cụ ký ứng dụng nào bạn đang sử dụng:
* **Nếu có chứng chỉ `.p12` trên iPhone**: Mở **Feather**, **ESign**, **GBox** hoặc **Scarlet** $\rightarrow$ Nhập file `4AppleTV.ipa` $\rightarrow$ Bấm **Ký (Sign)** & **Cài đặt (Install)**.
* **Nếu dùng TrollStore**: Mở file `4AppleTV.ipa` trong **TrollStore** để cài đặt vĩnh viễn.
* **Nếu dùng SideStore / AltStore / Sideloadly**: Chọn cài đặt file `4AppleTV.ipa` bằng Apple ID cá nhân của bạn.

> 💡 **Lưu ý quan trọng khi mở ứng dụng lần đầu**: Khi iOS hỏi quyền **"4AppleTV muốn tìm và kết nối với các thiết bị trên mạng cục bộ của bạn (Local Network)"**, hãy bấm **Cho phép (Allow)**. Đây là quyền bắt buộc để iPhone nhìn thấy Apple TV qua mạng Wi-Fi.

---

### Bước 2: Kích hoạt Mã Bản Quyền (Sideload Pass)
Để sử dụng tính năng **Cài đặt & Làm mới ứng dụng `.IPA` lên Apple TV**, bạn cần kích hoạt mã bản quyền **Sideload Pass** (tính năng **Điều khiển từ xa** hoạt động tự do ngay khi ghép đôi):

1. Mở ứng dụng **4AppleTV** $\rightarrow$ Chuyển sang tab **Tài khoản** (biểu tượng hình người ở thanh công cụ dưới cùng).
2. Tại mục **Giấy phép (Sideload Pass)**, nhập mã bản quyền của bạn (định dạng `TVS-XXXX-XXXX`) vào ô **Mã kích hoạt**.
3. Bấm **Kích hoạt**. Hệ thống sẽ xác thực trực tuyến và gắn bản quyền với thiết bị của bạn.

#### 📌 Chính sách Bản quyền Sideload Pass v2.0:
* Mỗi mã bản quyền kích hoạt cho **01 thiết bị đang hoạt động (Active)** tại một thời điểm.
* Hỗ trợ **Đổi thiết bị (Đổi máy iPhone/iPad mới) tối đa 02 lần** hoàn toàn tự động ngay trong ứng dụng: Khi bạn nhập mã bản quyền lên máy mới, hệ thống sẽ tự động thu hồi quyền trên máy cũ và chuyển sang máy mới (số lượt đổi máy còn lại được hiển thị minh bạch).

---

### Bước 3: Kết nối & Ghép đôi với Apple TV (Thực hiện 1 lần duy nhất)
Đảm bảo **iPhone/iPad và Apple TV đang kết nối cùng một mạng Wi-Fi** (hoặc Apple TV cắm dây mạng LAN vào cùng Router Wi-Fi).

#### 3.1. Ghép đôi Điều khiển từ xa (Remote Pairing)
1. Trên Apple TV, vào **Cài đặt (Settings)** $\rightarrow$ **Điều khiển và Thiết bị (Remotes and Devices)** $\rightarrow$ **Ứng dụng Điều khiển và Thiết bị (Remote App and Devices)**.
2. Trên iPhone, mở **4AppleTV** $\rightarrow$ Tab **Điều khiển** (hoặc Tab **Thiết bị**).
3. Chọn tên Apple TV của bạn trong danh sách phát hiện tự động $\rightarrow$ Bấm **Ghép đôi Điều khiển**.
4. Nhập **Mã PIN 4 chữ số** hiển thị trên màn hình TV vào iPhone $\rightarrow$ Hoàn tất! Giờ đây bạn có thể điều khiển Apple TV và mở nhanh ứng dụng từ iPhone.

#### 3.2. Ghép đôi Cài đặt Ứng dụng (Developer / Sideload Pairing)
Để bắn file `.ipa` không dây sang Apple TV, bạn cần ghép đôi chế độ Nhà phát triển (tương tự thao tác Pair Xcode):
1. Trên Apple TV, giữ màn hình ở mục **Cài đặt (Settings)** $\rightarrow$ **Điều khiển và Thiết bị (Remotes and Devices)** $\rightarrow$ **Ứng dụng Điều khiển và Thiết bị (Remote App and Devices)**.
2. Trên iPhone, mở **4AppleTV** $\rightarrow$ Chuyển sang tab **Thiết bị** $\rightarrow$ Bấm nút **Ghép đôi mới (+)** ở góc trên bên phải.
3. Chạm vào tên Apple TV của bạn khi xuất hiện trong danh sách quét mạng.
4. Một **Mã PIN 6 chữ số** sẽ hiện lên trên màn hình Apple TV $\rightarrow$ Nhập mã 6 số này vào ứng dụng 4AppleTV trên iPhone.
5. Ngay sau khi ghép đôi thành công, 4AppleTV sẽ tự động lưu khóa kết nối và hiển thị đầy đủ **UDID** của Apple TV.

---

### Bước 4: Thiết lập Tài khoản Ký Ứng Dụng (Tab **Tài khoản**)
Bạn có thể chọn **1 trong 2 cách** dưới đây tùy theo nhu cầu:

#### Cách A: Sử dụng Chứng chỉ `.p12` + `.mobileprovision` (Khuyên dùng nếu có chứng chỉ năm)
1. Đảm bảo UDID của Apple TV (hiển thị ở tab **Thiết bị** trong 4AppleTV) đã được thêm vào danh sách thiết bị của chứng chỉ.
2. Vào tab **Tài khoản** $\rightarrow$ Mục **Chứng chỉ P12 & Provision (.p12 + .mobileprovision)**.
3. Bấm **Chọn file .p12** $\rightarrow$ Nhập **Mật khẩu chứng chỉ .p12**.
4. Bấm **Chọn file .mobileprovision** (file cấu hình cấp phép có chứa UDID Apple TV).
5. Bấm **Lưu & Kiểm tra chứng chỉ**. Khi ứng dụng báo **Đã sẵn sàng (Hợp lệ)**, bạn có thể cài đặt không giới hạn số lượng ứng dụng lên Apple TV với thời hạn theo chứng chỉ (1 năm).

#### Cách B: Sử dụng Tài khoản Apple ID Miễn phí (Không tốn phí mua chứng chỉ)
1. Vào tab **Tài khoản** $\rightarrow$ Mục **Tài khoản Apple ID (Developer / Miễn phí)**.
2. Nhập **Email Apple ID** và **Mật khẩu** của bạn $\rightarrow$ Bấm **Đăng nhập**.
3. Nhập mã xác thực 2 yếu tố (2FA - 6 chữ số) được gửi về iPhone của bạn.
4. *(Lưu ý của Apple đối với tài khoản miễn phí: Mỗi Apple ID miễn phí được phép cài đặt tối đa 3 ứng dụng cùng lúc và chứng chỉ có hiệu lực 7 ngày — 4AppleTV sẽ tự động làm mới trước khi hết hạn).*

---

### Bước 5: Bật Chế Độ Nhà Phát Triển (Developer Mode) Trên Apple TV (Bắt buộc trên tvOS 16+)
Khi bạn cài đặt ứng dụng đầu tiên lên Apple TV chạy tvOS 16, 17, 18 trở lên, Apple yêu cầu bật **Developer Mode**:
1. Sau khi 4AppleTV đẩy ứng dụng đầu tiên lên, trên Apple TV hãy vào **Cài đặt (Settings)** $\rightarrow$ **Quyền riêng tư và Bảo mật (Privacy and Security)** $\rightarrow$ Kéo xuống cuối chọn **Chế độ Nhà phát triển (Developer Mode)**.
2. Gạt bật **Developer Mode** $\rightarrow$ Apple TV sẽ khởi động lại (Restart).
3. Sau khi khởi động lại, màn hình TV sẽ hiện bảng xác nhận $\rightarrow$ Chọn **Bật (Turn On)** và xác nhận. Từ lần sau trở đi bạn không cần làm lại bước này nữa.

---

### Bước 6: Cài Đặt File `.IPA` Lên Apple TV (Tab **Cài app**)
1. Tải các file `.ipa` dành cho **Apple TV (tvOS)** về ứng dụng **Tệp (Files)** trên iPhone.
2. Mở **4AppleTV** $\rightarrow$ Chuyển sang tab **Cài app** $\rightarrow$ Bấm nút **Cài đặt IPA (+)** ở góc trên bên phải.
3. Chọn file `.ipa` tvOS bạn muốn cài.
4. Chọn chiếc Apple TV đích (nếu nhà bạn có nhiều Apple TV).
5. Thanh tiến trình phía dưới màn hình sẽ tự động thực hiện toàn bộ quy trình:
   * *Giải nén gói IPA* $\rightarrow$ *Cấp phát chứng chỉ & Provisioning Profile* $\rightarrow$ *Ký số nhị phân (Code Signing)* $\rightarrow$ *Truyền tải qua Wi-Fi & Cài đặt lên Apple TV*.
6. Khi thông báo **"Cài đặt hoàn tất!"** xuất hiện, biểu tượng ứng dụng mới sẽ hiện ngay trên màn hình chính của Apple TV và trong tab **Ứng dụng** của 4AppleTV!

---

## 🔄 4. Hướng Dẫn Sử Dụng Chế Độ Tự Động Cập Nhật (Auto-Update)

**4AppleTV** được tích hợp sẵn bộ kiểm tra cập nhật thông minh (`UpdateChecker`):
1. Mở tab **Tài khoản** $\rightarrow$ Bấm biểu tượng **Bánh răng (Cài đặt)** ở góc trên bên phải.
2. Tại mục **Cập nhật ứng dụng (Auto-Update)**:
   * **Tự động kiểm tra bản cập nhật khi mở app**: Mặc định luôn **Bật**. Mỗi khi có bản phát hành mới trên kho lưu trữ chính thức, ứng dụng sẽ tự động hiển thị bảng thông báo chi tiết những tính năng mới.
   * **Kiểm tra cập nhật ngay**: Bấm bất kỳ lúc nào để kiểm tra thủ công xem bạn đã ở bản dựng mới nhất chưa.
   * **Cập nhật 1 chạm**: Khi có bản mới, bấm **"Tải .IPA & Mở trong App Ký"** để ứng dụng tự tải file `4AppleTV.ipa` mới nhất và chuyển thẳng sang ứng dụng ký (*Feather / ESign / SideStore / AltStore / TrollStore*) cài đè lên bản hiện tại mà **giữ nguyên 100% mã bản quyền, tài khoản và danh sách Apple TV đã ghép đôi**.

---

## ❓ 5. Câu Hỏi Thường Gặp & Xử Lý Sự Cố (FAQ)

<details>
<summary><strong>1. Tại sao 4AppleTV không tìm thấy Apple TV của tôi trong mạng Wi-Fi?</strong></summary>
<br/>
<ul>
  <li>Kiểm tra xem iPhone và Apple TV có đang kết nối cùng một lớp mạng LAN/Wi-Fi hay không (tránh dùng mạng Wi-Fi Khách / Guest Network có bật <em>AP Isolation</em>).</li>
  <li>Vào <strong>Cài đặt iOS</strong> $\rightarrow$ <strong>Quyền riêng tư & Bảo mật</strong> $\rightarrow$ <strong>Mạng cục bộ (Local Network)</strong> $\rightarrow$ Đảm bảo công tắc của <strong>4AppleTV</strong> đang được <strong>Bật</strong>.</li>
  <li>Trên Apple TV, hãy mở màn hình <em>Settings $\rightarrow$ Remotes and Devices $\rightarrow$ Remote App and Devices</em> để kích hoạt phát tín hiệu quảng bá Bonjour.</li>
</ul>
</details>

<details>
<summary><strong>2. Tôi cài file .IPA nhưng báo lỗi không tương thích nền tảng (Platform Mismatch)?</strong></summary>
<br/>
<ul>
  <li>Hãy đảm bảo file <code>.ipa</code> bạn chọn là phiên bản được biên dịch cho <strong>tvOS (Apple TV)</strong> chứ không phải bản dành cho iPhone (iOS).</li>
</ul>
</details>

<details>
<summary><strong>3. Tôi đổi điện thoại iPhone mới thì mã bản quyền Sideload Pass có dùng lại được không?</strong></summary>
<br/>
<ul>
  <li><strong>Hoàn toàn được!</strong> Bạn chỉ cần cài 4AppleTV lên máy iPhone mới và nhập lại đúng mã bản quyền <code>TVS-XXXX-XXXX</code> của bạn. Hệ thống sẽ tự động thu hồi thiết bị cũ và kích hoạt cho thiết bị mới (mỗi mã được hỗ trợ đổi thiết bị tối đa <strong>02 lần</strong>).</li>
</ul>
</details>

---

<div align="center">
  <p>Phát triển & Phân phối bản quyền chính thức bởi <strong>Hồng Sơn (4AppleTV Team)</strong></p>
  <p>Liên hệ hỗ trợ & Mua mã bản quyền Sideload Pass: <a href="mailto:hongson1812@gmail.com">hongson1812@gmail.com</a></p>
</div>
