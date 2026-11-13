### 🎉 4AppleTV v1.1.0 — Đa Ngôn Ngữ (System / Tiếng Việt / English), Liên Hệ Hỗ Trợ & Bảo Vệ Chống Sao Chép BLA v3.3.0

#### 🇻🇳 Có gì mới trong bản v1.1.0:
- **Hỗ trợ Đa ngôn ngữ (`Theo hệ thống / Tiếng Việt / English`)**:
  - Tự động nhận diện ngôn ngữ hệ thống của iPhone/iPad (hiển thị Tiếng Việt trên máy Tiếng Việt và Tiếng Anh trên máy quốc tế).
  - Cho phép chuyển đổi ngôn ngữ trực tiếp ngay trong ứng dụng (**mà không cần khởi động lại app**) tại màn hình Kích hoạt, thanh công cụ Điều khiển (biểu tượng 🌐) và trong mục **Cài đặt ▸ Ngôn ngữ**.
  - Bản địa hóa hộp thoại xin quyền Mạng cục bộ iOS (`en.lproj` & `vi.lproj`) và thông báo từ nhân Rust.
- **Tích hợp thông tin liên hệ chính thức (`hongson1812@gmail.com`)**:
  - Hiển thị kèm nút gửi Email nhanh (`mailto:`) và nút Sao chép 1 chạm ngay trên màn hình Kích hoạt bản quyền, mục **Tài khoản** và mục **Cài đặt**.
- **Tích hợp Lá chắn Chống Sao Chép & Dịch Ngược AI (`BLA v3.3.0 — Counter-REA`)**:
  - Gia cố trực tiếp nhân nhị phân `arm64` Mach-O (Rust + C MBA Tarpit + Enclave Attestation) và gói Bundle (`EnclaveAttestation.plist`) chống lại các công cụ dịch ngược tự động, gắn kết mật mã (SHA-256 + Ed25519) giữa định danh `4AppleTV`, thông tin liên hệ chính chủ `hongson1812@gmail.com` và khóa xác thực bản quyền, đồng thời tương thích 100% với mọi trình ký iOS (*Feather, ESign, SideStore, AltStore, TrollStore, Sideloadly*).
- **Tự động cập nhật (In-App Auto-Update)**: Người dùng bản `v1.0.0` sẽ nhận thông báo cập nhật lên `v1.1.0` tự động ngay khi mở ứng dụng.

---

#### 🇬🇧 What's New in v1.1.0:
- **Multi-Language Support (`System Default / English / Tiếng Việt`)**:
  - Automatically matches your iPhone/iPad system language on launch, or switch instantly in-app via the 🌐 menu on the Remote / Activation screens or in **Settings ▸ Language**.
- **Official License & Technical Support Contact (`hongson1812@gmail.com`)**:
  - One-tap `mailto:` & copy buttons integrated into the Activation screen, **Account** tab, and **Settings**.
- **BLA v3.3.0 Counter-REA & Anti-Copying Shield**:
  - Hardened `arm64` Mach-O native core and bundle attestation with cryptographic brand entanglement while preserving 100% compatibility with standard iOS sideload signers (*Feather, ESign, SideStore, AltStore, TrollStore, Sideloadly*).
- **Direct Download**: Tap **`4AppleTV.ipa`** below to download and install on iOS/iPadOS 17.0+.
