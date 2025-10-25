[![GitHub release](https://img.shields.io/github/release/dino9193/vi-fortune.svg?style=plastic)](https://github.com/dino9193/vi-fortune/releases/latest)
[![License: GPL v3](https://img.shields.io/badge/License-GPL%20v3-blue.svg?style=plastic)](https://opensource.org/licenses/GPL-3.0)
[![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://github.com/dino9193/vi-fortune)

# vi-fortune

fortune tiếng việt (không phải dịch đâu)

## Công dụng

Không cần thiết lắm nhưng tác dụng của nó là:

- Bổ sung thành ngữ tiếng việt cho fortune.

## Cách cài đặt

### Arch linux (Manjaro, ArcoLinux)

Đã có sẵn trên AUR :

[![AUR version](https://img.shields.io/aur/version/vi-fortune?style=plastic&logo=archlinux&logoColor=white)](https://aur.archlinux.org/packages/vi-fortune)

### Các distro (Bản phân phối) khác :

Đầu tiên các bạn cần xác định nơi chứa các cookies fortune của bạn bằng cách dùng lệnh :

```bash
fortune -f
```

Đầu ra sẽ trông như thế này :

```output
100,00% /usr/share/fortune
     4,36% archlinux
     2,91% art
     0,06% ascii-art
     6,53% computers
     6,96% cookie
     0,52% debian
     7,38% definitions
     1,74% disclaimer
     1,27% drugs
     1,26% education
     0,99% ethnic
     1,20% food
     2,64% fortunes
     0,32% goedel
     1,21% humorists
     0,93% kids
     3,31% knghtbrd
     1,26% law
     2,44% linux
     1,60% literature
     0,92% love
     0,18% magic
     0,45% medicine
     3,56% men-women
     3,95% miscellaneous
     0,32% news
     0,43% paradoxum
     7,63% people
     1,67% perl
     0,31% pets
     3,04% platitudes
     4,28% politics
     0,02% pratchett
     0,78% riddles
     0,98% rules-of-acquisition
     3,82% science
     1,52% shlomif-fav
     4,34% songs-poems
     0,90% sports
     1,40% startrek
     0,50% tao
     0,15% the-x-files-taglines
     0,07% translate-me
     0,07% vi-fortune
     2,62% wisdom
     3,84% work
     3,35% zippy
```

Ở phần `100,00% /usr/share/fortune` thì phần `/usr/share/fortune` chính là đường dẫn. Nó sẽ thay đổi theo distro của bạn (còn ở đây là Arch).

Tiếp theo các bạn sẽ vào [![GitHub release](https://img.shields.io/github/release/dino9193/vi-fortune.svg?style=plastic)](https://github.com/dino9193/vi-fortune/releases/latest) tải file vi-fortune.dat về cho mình. Rồi copy file vi-fortune.dat vào thư mục bạn vừa tìm được.

Vậy là các bạn đã cài đặt xong

## Mẹo

- Các bạn có thể mở file .bashrc (hoặc .zshrc hay cái gì đấy khác thường thường là .bashrc bạn dùng cái khác thì chắc bạn biết rõ) rồi paste dòng này vào và lưu lại :

```sh
alias vi-fortune='fortune vi-fortune'
```

Khi dùng lệnh `vi-fortune` thì nó sẽ không hiện các câu tiếng anh mà chỉ câu tiếng việt thôi.

## Báo cáo lỗi

Thực ra gói này rất nhỏ và chắc là chả cần đâu (cú pháp cookies fortune rất đơn giản) nhưng bạn có thể dùng [trang báo cáo lỗi của Github](https://github.com/dino9193/vi-fortune/issues) khoảng cuối tuần mình sẽ trả lời.
