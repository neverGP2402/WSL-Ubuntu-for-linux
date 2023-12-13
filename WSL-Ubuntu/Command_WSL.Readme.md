
# WSL-Ubuntu-for-linux [(Github version)](https://github.com/neverGP2402/WSL-Ubuntu-for-linux.git)

## Update and Upgrade
`Update`: Kiểm tra cập nhật các phiên bản của package
```vim
sudo apt update 
```

`Upgrade `: Sau khi đã kiểm tra cập nhật xong nếu muốn cập nhật lên thì gõ lệnh sau:
```vim
sudo apt updgrade 
```

## Lệnh `ls`, `cd` trên Ubuntu/Linux
### `1. ls`
Lấy danh sách các file trong thư mục hiện tại đang đứng
```vim
ls -<option>
```
 `-l` xem dạng danh sách,
 `-a` Xem tất cả file ẩn trong thu mục hiện tại


### `2. cd`
Lấy danh sách các file trong thư mục hiện tại đang đứng
```vim
cd <option>
```
 `-` Quay lại đường dẫn gần nhất khi thao tác,
 `..` Quay lại đường dẫn 1 cấp,
 `path name` di chuyển đến thu mục dựa vào đường dẫn


## Lệnh mkdir, touch, vi trong Linux
`1. mkdir`: Viết tắt của make directory - tạo thư mục 
```vim
mkdir ten-thu-muc
```
Hoặc
```vim
mkdir path/ten-thu-muc
```
Với `path` là đường dẫn thu mục với điều kiện là đường dẫn thư mục đã tồn tại với tạo thu mực theo đường dẫn không tồn tại thì thêm option là `-p` thì sẽ tạo hết tất cả thu mục có trong đường dẫn được chỉ định ví dụ:
``` vim
mkdir -p folder-1/folder-2/folder-new
```
Với câu lệnh này thì đồng thời sẽ tạo ra 3 thu mục `folder-1`, `folder-2` và `folder-new` (nếu chưa có)

 Ngoài ra còn có `rm` và `rmdir` viết tắt của remove và remove directory tức là xóa thu mục hoặc file
#### Xóa thu mục
``` vim
rmdir path/ten-thu-muc 
```
`rmdir` chỉ xóa thu mục rỗng còn muốn xóa, thư mục đã tồn tại file hoặc thư mục con trong đó ta dùng `rm -r`
```vim
rm -r path/folder-name
```
#

`2.touch `: Tạo file không cần thêm nội dung
```vim
touch path/file_name.file_type
```
#

#
`3.vi `: Tạo file và ghi file, vi viết tắt của từ `vim`
```vim
vi file_name.file_type
```
Khi gõ câu lệnh này sẽ mở ra trình soạn thảo ngay trên terminal và ở đây chỉ có thể sử dụng bàn phím và không thể sử dụng chuột
#### Các lệnh để thao tác và soạn thảo ngay trên terminal
- `i`: bật chế độ insert mode có thể ghi file và soạn thảo, khi ở chế độ này nhấn phím `esc`
``` javascript
:q // Thoát và không lưu
:wq! OR :x //Thoát và luu
```
 
## Minimal [(Free version)](https://minimal-kit-react.vercel.app/)

![license](https://img.shields.io/badge/license-MIT-blue.svg)

> Free React Admin Dashboard made with Material-UI components and React.

![preview](public/assets/preview.jpg)

| [Minimal Free](https://minimal-kit-react.vercel.app/) | [Minimal](https://material-ui.com/store/items/minimal-dashboard/) |
| ----------------------------------------------------- | :---------------------------------------------------------------- |
| **6** Demo pages                                      | **50+** demo pages                                                |
| -                                                     | ✓ Multi-language                                                  |
| -                                                     | ✓ Dark/Light Mode 🌓                                              |
| -                                                     | ✓ [More components](https://minimals.cc/components)               |
| -                                                     | ✓ Next.js version                                                 |
| -                                                     | ✓ TypeScript version                                              |
| -                                                     | ✓ Design files (Figma & Sketch)                                   |

## Page demo

- [Dashboard](https://minimal-kit-react.vercel.app/dashboard/app)
- [Users](https://minimal-kit-react.vercel.app/dashboard/user)
- [Product](https://minimal-kit-react.vercel.app/dashboard/products)
- [Blog](https://minimal-kit-react.vercel.app/dashboard/blog)
- [Login](https://minimal-kit-react.vercel.app/login)
- [Not Found](https://minimal-kit-react.vercel.app/404)

## Getting started

- Recommended `node js 16.x` and `npm 6+`. (suggestion v16.15.0)
- Install dependencies: `npm install` / `yarn install`
- Start the project: `npm run start` / `yarn start`

## License

Distributed under the MIT License. See [LICENSE](https://github.com/minimal-ui-kit/minimal.free/blob/main/LICENSE.md) for more information.

## Contact us

Email Us: support@minimals.cc
