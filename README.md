# Đố Vui Game

Thư viện quiz kiến thức game. Mở đầu với **Liên Quân Mobile** và **PUBG**, mỗi game có 4 bộ câu hỏi (kiến thức game, chi tiết trong game, thuật ngữ game thủ, cảm xúc game thủ) và một mục ôn tập tổng hợp.

Chơi tại: https://fudoyuser.github.io/game/

## Thêm game mới

Mở `index.html`, thêm một object vào mảng `FILMS` (gồm `id`, `motif`, `title`, `original`, `meta`, `epLabel`, các mảng nguồn và `questions`, `episodes`, `terms`, `emotions`), rồi thêm một khối màu `[data-film="<id>"]` trong CSS. Mỗi câu hỏi có `q` (câu hỏi), `a` (đáp án đúng), `w` (3 đáp án sai), `e` (giải thích).
