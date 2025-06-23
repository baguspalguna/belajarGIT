# belajarGIT

## How to Clone and Accessing Repository

## Clone Using SSH
1. Harus ada repository Github. Copy URL SSH.
2. Buka terminal (cmd, powershell, bash) dengan working directory di folder yang mana kita ingin menyimpan repository tsb.
3. Dalam terminal gunakan command `git clone <url ssh>`
4. Repository akan terbentuk di folder tersebut.

Selanjutnya buka working directory di repository atau langsung buka vscode di repository

## Track and Commit File(s) Changes

1. Cek status files dalam repository dengan `git status`
2. Track perubahan gunakan `git add <nama file>`untuk 1 file saja atau `git add .` untuk semua file.
3. Kalau cek `git status`lagi file akan berubah jadi tracked dan siap commit.
4. Untuk menyimpan perubahan lakukan dengan `get commit -m "commit message"`. Commit message biasanya diatur dalam commit message convention, bisa lihat di internet.
(kalau gak jadi commit bisa `git reset --mixed`atau `git revert`)
5. Menyimpan perubahan ke repository remote lakukan `git push`
