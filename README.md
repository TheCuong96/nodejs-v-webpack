# Để học được reactjs thì trước tiên ta phải setup môi trường cho nó, đó là nodejs, bình thường thì ta sẽ mở trình duyệt lên để chạy javascript nhưng bây giờ ta cài nodejs vào thì nó có thể chạy trên hệ điều hành của chúng ta [Đây là web gốc của nodejs, ta có thể vào đây và download để cài ](https://nodejs.org/en/)

Nhưng ta sẽ không cài thằng trên mà ta vào gg tìm từ Node.js version manager này ra để vào github của nó mà cài vào, cài thằng này cũng như cài nodejs nhưng nó được làm lại và có thể quản lý version của node 1 cách nhanh và thuận tiện hơn...[Node.js version manager, sẽ có 2 phiên bản của window và macOS nên tìm hiểu kỹ trước khi cài](https://github.com/coreybutler/nvm-windows)

[đây là link download của Node.js version manager, ở trên có thể hiểu là link trang chủ](https://github.com/coreybutler/nvm-windows/releases).

## Kiểm tra xem nó đã cài thành công chưa `nvm -v`

nếu nó show ra 1 version thì nó đã cài thành công

- Và sau khi ta cài xong nvm cũng có nghĩa là nodejs thì ta có thể dùng npm, npm nghĩa là node package manager, thì npm nó giúp chúng ta quản lý các gói package 1 cách thuận tiện hơn
- Bây giờ nếu ta muốn cài đặt 1 thư viện hay framework nào đó thì ta có thể ghi `npm install name-framework`
- nếu muốn xóa thì `npm uninstall name-framework`

### `yarn`

Thì sau khi cài npm thì ta nên cài yarn
yarn nó giúp ta quản lý package thuận tiện hơn npm, nó chạy nhanh hơn npm khi ta quản lý các packake, ví dụ như khi trong package của ta có nhiều framework thì khi cài bằng yarn nó sẽ đồng loạt chạy hết tất cả framework đó để cài 1 lần, còn npm thì sẽ cài từng cái và lâu hơn...
[yarn add](https://yarnpkg.com/getting-started/install)

### `action`

sau đó ta tạo file namefile.js và cửa sổ terminal và chạy file namefile.js đó lên bằng câu lệnh `node namefile.js`

### `nodemon`

nodemon này dùng để nó liên tục cập nhật và update khi ta đang chạy node `npm i nodemon` [cài đặt nodemon](https://www.npmjs.com/package/nodemon)
