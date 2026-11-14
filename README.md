<div align="center">
  <img src="docs/icon.png" alt="4AppleTV Logo" width="160" style="border-radius: 36px; box-shadow: 0 12px 32px rgba(10,132,255,0.35);" />
  <h1>4AppleTV</h1>
  <p><strong>Trung tâm Điều khiển Apple TV, Kho Ứng Dụng GitHub & Cài đặt Ứng dụng (.IPA) Không dây từ iPhone / iPad</strong></p>

  <p>
    <a href="https://github.com/hongson117/4AppleTV/releases/latest/download/4AppleTV.ipa">
      <img src="https://img.shields.io/badge/Tải_Về_Ngay-4AppleTV.ipa-0A84FF?style=for-the-badge&logo=apple&logoColor=white" alt="Tải về 4AppleTV.ipa" />
    </a>
    <a href="https://github.com/hongson117/4AppleTV/releases/latest">
      <img src="https://img.shields.io/github/v/release/hongson117/4AppleTV?style=for-the-badge&label=Phiên_bản_Mới_nhất&color=30D158" alt="Phiên bản mới nhất" />
    </a>
    <a href="https://github.com/hongson117/InfinitySideload-releases">
      <img src="https://img.shields.io/badge/Khuyên_dùng_trên_iOS-∞Sideload-FF9F0A?style=for-the-badge" alt="∞Sideload" />
    </a>
    <img src="https://img.shields.io/badge/iOS_%2F_iPadOS-17.0%2B-5E5CE6?style=for-the-badge" alt="iOS 17.0+" />
    <img src="https://img.shields.io/badge/tvOS-15.0%2B-1C1C1E?style=for-the-badge&logo=appletv" alt="tvOS 15.0+" />
  </p>
</div>

---

## 🌟 1. Giới Thiệu & Miêu Tả Chi Tiết Sản Phẩm (Overview)

**4AppleTV** là ứng dụng chuyên dụng dành cho người dùng **Apple TV HD / Apple TV 4K** trên nền tảng **iPhone và iPad (iOS/iPadOS 17.0+)**. Được thiết kế với kiến trúc lõi **Rust (`libtvs_core`)** kết hợp giao diện **SwiftUI Native Đa ngôn ngữ (`Theo hệ thống / Tiếng Việt / English`)**, **4AppleTV** hợp nhất trọn vẹn ba nhu cầu cốt lõi của người dùng Apple TV vào một ứng dụng duy nhất:

1. **Điều khiển từ xa (Smart Remote) & Mở nhanh ứng dụng trên Apple TV** với độ trễ cực thấp qua giao thức Apple Companion Link chính gốc.
2. **Thư viện ứng dụng GitHub cho tvOS tích hợp sẵn** (*Orivio TV, Nuvio TV, Yattee, LiveContainerTV*) kèm khả năng tự thêm kho GitHub `owner/repo`, link release/tag, link `.ipa` trực tiếp hoặc nguồn AltStore/Feather `source.json`.
3. **Cài đặt & Làm mới ứng dụng (`.ipa` Sideloading) không dây qua mạng Wi-Fi** trực tiếp từ iPhone lên Apple TV **mà không cần máy tính Mac, không cần Xcode và không cần dây cáp USB-C**.

> 🇬🇧 **English Summary**: **4AppleTV** natively supports **English**, **Vietnamese**, and **System Default** languages (switchable live in-app via the 🌐 globe button or **Settings ▸ Language**). Starting in **v1.2.0**, it combines an ultra-low-latency Apple TV Remote + 1-tap TV App Launcher, a curated & custom **GitHub tvOS App Library** (*Orivio TV, Nuvio TV, Yattee, LiveContainerTV*), **SHA-256 verified updates**, and a reliable **Auto-Refresh Coordinator** with post-install bundle verification on Apple TV. For iOS/iPadOS 17.4+ sideloading, we officially recommend **[∞Sideload (InfinitySideload)](https://github.com/hongson117/InfinitySideload-releases)**, which shares Sideload Pass compatibility. Support & licensing: **[hongson1812@gmail.com](mailto:hongson1812@gmail.com)**.

---

### 🔥 Các Tính Năng Nổi Bật Của 4AppleTV

#### 🎮 1. Điều Khiển Apple TV Toàn Diện (Tab **Điều khiển**)
* **Hai chế độ điều khiển linh hoạt**: Chuyển đổi tức thì giữa **Bề mặt cảm ứng vuốt (Touchpad)** mượt như Siri Remote thật và **Cụm phím điều hướng 5 chiều (D-Pad)** chính xác từng nhịp bấm.
* **Tùy chỉnh độ nhạy Touchpad**: Điều chỉnh độ nhạy vuốt từ `0.4x` đến `2.2x` phù hợp với thói quen sử dụng của từng người.
* **Đầy đủ phím chức năng phần cứng**: Nguồn (Bật/Tắt TV), Tắt tiếng (Mute), Tăng/Giảm âm lượng, Quay lại (Back/Menu), Màn hình chính (TV/Home), Phát/Tạm dừng (Play/Pause), Tua lùi 10s, Tua tới 10s.
* **Bàn phím Tiếng Việt có dấu tức thì**: Nhập văn bản tìm kiếm phim, YouTube, mật khẩu Wi-Fi hoặc tài khoản trên Apple TV ngay từ bàn phím iPhone với hỗ trợ đầy đủ Tiếng Việt Unicode.
* **Phản hồi xúc giác (Haptic Feedback)**: Từng thao tác chạm và điều hướng đều có phản hồi rung tinh tế giúp điều khiển không cần nhìn màn hình điện thoại.

#### 🚀 2. Lưới Ứng Dụng TV & Mở Nhanh 1 Chạm (Tab **Ứng dụng**)
* **Hiển thị trực quan ứng dụng trên Apple TV**: Tự động đồng bộ danh sách các ứng dụng đã cài qua 4AppleTV và các ứng dụng phổ biến (*Orivio TV, Nuvio TV, Yattee, LiveContainerTV, VPhimTV, AceSport TV, FPT Play, TV360, Infuse, MultiTVOS, YouTube, Netflix...*).
* **Mở ứng dụng tức thì (1-Tap Launch)**: Chạm vào biểu tượng ứng dụng trên iPhone để mở ngay ứng dụng đó trên màn hình Apple TV.
* **Tự động chuyển sang Remote**: Sau khi bấm mở ứng dụng trên TV, 4AppleTV tự động đưa bạn về màn hình **Điều khiển** để thao tác ngay lập tức.

#### 📚 3. Thư Viện Ứng Dụng GitHub & Nguồn Tùy Chỉnh (Tab **Cài app ▸ Thư viện GitHub**)
* **Kho tuyển chọn sẵn sàng cho tvOS**: Tải & cài đặt trực tiếp các ứng dụng mã nguồn mở/phát hành công khai nổi bật cho Apple TV:
  * **Orivio TV** (`prehakanson-art/OrivioTVAppleTV`)
  * **Nuvio TV** (`bobsupra/NuvioTVOS` — tự động nhận diện bản tvOS pre-release chuẩn)
  * **Yattee** (`yattee/yattee` — tự động lọc đúng gói `tvOS.ipa`)
  * **LiveContainerTV** ([`hongson117/LiveContainerTV-releases`](https://github.com/hongson117/LiveContainerTV-releases) — kèm mã kiểm tra toàn vẹn `SHA-256`)
* **Hỗ trợ 8 định dạng nguồn tự thêm**: Dán trực tiếp `owner/repo`, link GitHub repo, `/releases`, `/releases/tag/<tag>` (hỗ trợ cả tag có dấu `/`), link tải `.ipa` trên GitHub, link HTTPS `.ipa` trực tiếp hoặc manifest `source.json` chuẩn AltStore / SideStore / Feather.
* **Kiểm định an toàn trước khi ký**: Tự động kiểm tra `Info.plist` và kiến trúc nhị phân Mach-O `arm64` cho tvOS, chặn sớm các gói nhầm sang iOS/macOS hoặc Apple TV Simulator, đồng thời giữ khóa biến thể (variant lock) và tài khoản ký khi cập nhật để bảo vệ dữ liệu ứng dụng trên TV.

#### 📦 4. Cài Đặt `.IPA` Không Dây Lên Apple TV (Tab **Cài app ▸ Đã cài đặt**)
* **Hoàn toàn không cần máy tính (PC-Free / Mac-Free)**: Chọn file `.ipa` dành cho tvOS từ ứng dụng **Tệp (Files)** hoặc tải thẳng từ **Thư viện GitHub** và cài không dây sang Apple TV qua Wi-Fi/LAN.
* **Xác minh sau cài đặt trên Apple TV**: Đối chiếu trực tiếp trạng thái bundle thực tế trên Apple TV sau mỗi lần cài đặt/làm mới để không báo thành công giả.
* **Hỗ trợ cả 2 phương thức ký ứng dụng**:
  1. **Tài khoản Apple ID miễn phí (Free Developer Account)**: Tự động đăng ký thiết bị, cấp Provisioning Profile và ký `.ipa` ngay trên iPhone (hỗ trợ tối đa 3 tài khoản Apple ID).
  2. **Chứng chỉ mua ngoài (`.p12` + `.mobileprovision`)**: Dành cho người dùng có chứng chỉ năm (không cần làm mới chu kỳ 7 ngày).

#### 🔄 5. Làm Mới Chứng Chỉ Đáng Tin Cậy (Auto-Refresh Coordinator)
* **Chính sách minh bạch theo từng ứng dụng**: Ưu tiên làm mới quanh giờ đã chọn (mặc định **03:00 theo giờ địa phương**) khi hệ thống iOS cho phép, kết hợp **2 chế độ lựa chọn** (*Mỗi ngày — chu kỳ ≥ 12 giờ* hoặc *Khi sắp hết hạn — còn ≤ 3 ngày*, luôn ưu tiên khẩn cấp ứng dụng còn ≤ 24 giờ).
* **Đa lớp kích hoạt an toàn**: Kết hợp `BGProcessingTask`, `BGAppRefreshTask`, **Tự động làm mới bù khi mở lại ứng dụng (Foreground Catch-up)** và **Intent Phím tắt Tự động hóa cá nhân (Shortcuts Personal Automation)** kèm **Lịch sử 20 phiên gần nhất** và thông báo trung thực khi cần người dùng can thiệp (như xác thực 2FA hoặc Apple TV không trực tuyến trên mạng LAN).

#### 🔄 6. Cập Nhật Phiên Bản Mới Đã Xác Minh SHA-256 (Verified Updates)
* **Kiểm tra & Xác minh toàn vẹn SHA-256**: Đối chiếu đồng nhất giữa GitHub Releases API và `version.json`, tải streaming `.ipa` kèm kiểm tra dung lượng trống và mã băm `SHA-256` trước khi mở bảng cài đặt.
* **Chuyển tiếp cài đè an toàn**: Chuyển file `.ipa` đã xác minh sang **[∞Sideload](https://github.com/hongson117/InfinitySideload-releases)**, **Feather**, **SideStore**, **AltStore**, **ESign** hoặc **TrollStore**.
* **Lưu ý giữ dữ liệu**: Khi cài đè bằng **cùng công cụ ký / cùng Apple ID hoặc chứng chỉ `.p12`** đã dùng trước đó, toàn bộ mã bản quyền Sideload Pass, khóa ghép đôi Apple TV và lịch sử ứng dụng được giữ nguyên 100%.

#### 🛡️ 7. Bảo Mật Cấp Độ Cao, Chống Sao Chép BLA & Chẩn Đoán Minh Bạch
* **Lưu trữ khóa an toàn trong iOS Keychain**: Mật khẩu Apple ID, GitHub PAT tùy chọn (chỉ gửi tới `api.github.com`, tự động gỡ bỏ khi redirect tải file), khóa ghép đôi và chứng chỉ `.p12` được lưu mã hóa trong **iOS Keychain**.
* **Bảo vệ chống sao chép BLA Counter-REA Shield**: Nhân nhị phân `arm64` và gói Bundle được gia cố đa lớp, tương thích hoàn toàn với mọi công cụ ký lại trên iOS.

---

## 📥 2. Tải Về & Hệ Sinh Thái Chính Thức

| Hạng mục | Liên kết trực tiếp |
| :--- | :--- |
| **Gói cài đặt iOS/iPadOS (`.ipa`)** | [**⬇️ Tải xuống `4AppleTV.ipa` (Bản mới nhất)**](https://github.com/hongson117/4AppleTV/releases/latest/download/4AppleTV.ipa) |
| **Trang Releases (Lịch sử phiên bản & SHA-256)** | [https://github.com/hongson117/4AppleTV/releases](https://github.com/hongson117/4AppleTV/releases) |
| **Nguồn Repo (AltStore / SideStore / Feather / ∞Sideload)** | `https://raw.githubusercontent.com/hongson117/4AppleTV/main/source.json` |
| **Feed Kiểm tra Cập nhật Đã Xác Minh (`version.json`)** | `https://raw.githubusercontent.com/hongson117/4AppleTV/main/version.json` |
| **Catalog Thư viện GitHub (`library.json`)** | `https://raw.githubusercontent.com/hongson117/4AppleTV/main/library.json` |
| **Trình cài đặt iOS khuyên dùng: ∞Sideload (`InfinitySideload`)** | [https://github.com/hongson117/InfinitySideload-releases](https://github.com/hongson117/InfinitySideload-releases) |

### Cách thêm nhanh nguồn Repo vào ∞Sideload / Feather / SideStore / AltStore / ESign:
Sao chép đường dẫn dưới đây và dán vào mục **Sources / Kho nguồn** trong ứng dụng ký của bạn:
```text
https://raw.githubusercontent.com/hongson117/4AppleTV/main/source.json
```

> 💡 **Gợi ý cho iPhone / iPad (iOS/iPadOS 17.4+)**: Chúng tôi khuyên dùng **[∞Sideload (InfinitySideload)](https://github.com/hongson117/InfinitySideload-releases)** — trình cài đặt tối ưu thế hệ mới cho iOS/iPadOS 17.4+, dùng chung hệ sinh thái mã **Sideload Pass (`TVS-...` / `ISL-...`)**.

---

## 📖 3. Hướng Dẫn Sử Dụng Chi Tiết Từ A – Z

### Bước 1: Cài đặt `4AppleTV.ipa` lên iPhone hoặc iPad
Bạn có thể cài đặt file [`4AppleTV.ipa`](https://github.com/hongson117/4AppleTV/releases/latest/download/4AppleTV.ipa) lên iPhone/iPad (iOS/iPadOS 17.0+) bằng trình ký bạn đang sử dụng:
* **Trên iOS/iPadOS 17.4+ với ∞Sideload**: Tải từ [`InfinitySideload-releases`](https://github.com/hongson117/InfinitySideload-releases) hoặc nhập file `4AppleTV.ipa` / nguồn `source.json` để ký và cài đặt.
* **Nếu có chứng chỉ `.p12` trên iPhone**: Mở **Feather**, **ESign**, **GBox** hoặc **Scarlet** → Nhập file `4AppleTV.ipa` → Bấm **Ký (Sign)** & **Cài đặt (Install)**.
* **Nếu dùng TrollStore / SideStore / AltStore / Sideloadly**: Mở hoặc nhập file `4AppleTV.ipa` để cài đặt.

> 💡 **Quyền Mạng Cục Bộ (Local Network)**: Khi mở ứng dụng lần đầu, hãy bấm **Cho phép (Allow)** khi iOS hỏi quyền tìm thiết bị trên mạng cục bộ để iPhone kết nối được với Apple TV qua Wi-Fi/LAN.

---

### Bước 2: Kích hoạt Mã Bản Quyền (Sideload Pass)
1. Mở ứng dụng **4AppleTV** → Chuyển sang tab **Tài khoản**.
2. Tại mục **Giấy phép (Sideload Pass)**, nhập mã bản quyền của bạn (`TVS-XXXX-XXXX` hoặc mã tương thích hệ sinh thái Sideload Pass) → Bấm **Kích hoạt**.
3. Mỗi mã kích hoạt cho **01 thiết bị đang hoạt động** và hỗ trợ **tự động chuyển đổi thiết bị tối đa 02 lần** khi bạn đổi sang iPhone/iPad mới.

---

### Bước 3: Kết nối & Ghép đôi với Apple TV (Thực hiện 1 lần)
Đảm bảo **iPhone/iPad và Apple TV đang kết nối cùng mạng LAN/Wi-Fi**.

#### 3.1. Ghép đôi Điều khiển từ xa (Remote Pairing)
1. Trên Apple TV: Vào **Settings → Remotes and Devices → Remote App and Devices**.
2. Trên iPhone: Mở **4AppleTV → Điều khiển** (hoặc **Thiết bị**) → Chọn tên Apple TV → Nhập **Mã PIN 4 chữ số** hiện trên TV.

#### 3.2. Ghép đôi Cài đặt Ứng dụng (Developer / Sideload Pairing)
1. Giữ màn hình Apple TV tại **Settings → Remotes and Devices → Remote App and Devices**.
2. Trên iPhone: Mở **4AppleTV → Thiết bị → Ghép đôi mới (+)** → Chọn Apple TV → Nhập **Mã PIN 6 chữ số** hiện trên màn hình TV. Ứng dụng sẽ lưu hồ sơ ghép đôi và hiển thị **UDID** của Apple TV.

---

### Bước 4: Thiết lập Tài khoản Ký & Cài Đặt Ứng Dụng Lên Apple TV
1. Vào tab **Tài khoản**: Đăng nhập **Apple ID miễn phí** (kèm 2FA) hoặc nhập **Chứng chỉ `.p12` + `.mobileprovision`** có chứa UDID Apple TV.
2. *(Trên Apple TV chạy tvOS 16+, vào **Settings → Privacy and Security → Developer Mode** để bật Chế độ Nhà phát triển trong lần cài đầu tiên).*
3. Chuyển sang tab **Cài app**:
   * **Cài từ Thư viện GitHub**: Chuyển sang mục **Thư viện GitHub**, chọn ứng dụng có sẵn (*Orivio TV, Nuvio TV, Yattee, LiveContainerTV*) hoặc bấm **Thêm nguồn GitHub / .ipa** → Kiểm tra thông tin gói, chọn **Apple TV đích** & **Tài khoản ký** → Bấm **Tải & Cài lên TV**.
   * **Cài file `.ipa` có sẵn trên máy**: Ở mục **Đã cài đặt**, bấm **Cài đặt file .ipa từ Tệp / iCloud** và chọn file tvOS `.ipa`.

---

### Bước 5: Thiết lập Làm Mới Tự Động Tối Ưu (Khuyên dùng cho Apple ID miễn phí)
1. Mở **Tài khoản → Cài đặt (biểu tượng bánh răng) → Làm mới chứng chỉ (.ipa)**.
2. Bật **Tự động làm mới ứng dụng tvOS**, chọn chế độ (**Mỗi ngày** hoặc **Khi sắp hết hạn**) và giờ ưu tiên (ví dụ `03:00`).
3. Để đạt độ ổn định cao nhất trên iOS, bấm vào mục **Hướng dẫn Tự động hóa Phím tắt (Khuyên dùng)** ngay trong Cài đặt để tạo 1 lịch *Tự động hóa cá nhân (Personal Automation)* trong app **Phím tắt (Shortcuts)** gọi thẳng tác vụ **“Làm mới ứng dụng Apple TV”** của 4AppleTV mỗi ngày và tắt *Hỏi trước khi chạy*.

---

<div align="center">
  <p>Phát triển & Phân phối bản quyền chính thức bởi <strong>Hồng Sơn (4AppleTV Team)</strong></p>
  <p>Liên hệ hỗ trợ & Mua mã bản quyền Sideload Pass: <a href="mailto:hongson1812@gmail.com">hongson1812@gmail.com</a></p>
</div>
