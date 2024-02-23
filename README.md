# node-gyp-fix
## Trong trường hợp terminal báo là thiếu python, sử dụng câu lệnh:
- npm install -g windows-build-tools

Câu lệnh này sẽ cài python vào máy, địa chỉ nhớ được cài cũng sẽ hiện thị trên terminal, lúc này nếu cài lại npm i vẫn gặp lỗi tương tự thì kiểm tra biến  python trong variable đã được cài đặt chưa, nếu chưa thì cài thêm vào "path" và biến PYTHON với đường dẫn vừa hiện trong terminal
## Trong trường hợp thiếu C++
Follow theo đường dẫn đc cung cấp trên terminal đến node-gyp truy cập vào phần C++ buildtool
link: https://github.com/nodejs/node-gyp?tab=readme-ov-file#on-windows
Đường dẫn nhấn vào để tải C++: https://visualstudio.microsoft.com/thank-you-downloading-visual-studio/?sku=BuildTools
Chỉ cần dán link vào trình duyệt là sẽ tự  tại file
Sau khi tải file về thì chỉ cần run file lên là được
## Các lỗi khác: 
có thể sử dụng thêm depend --ignore-scripts vào npm: "npm i --ignore-script" là có thể cài
