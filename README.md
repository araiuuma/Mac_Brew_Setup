## 1. 홈브루 설치하기
https://brew.sh/ko/

## 2. 홈브루 경로 설정
(한 줄 씩 터미널 복사)
'''
echo 'export PATH=/opt/homebrew/bin:$PATH' >> ~/.zshrc

source ~/.zshrc
'''

## 3. 홈브루 번들 다운
파일이 있는 폴더로 cd 후
'''
brew bundle
'''

### 설치 목록
tap "homebrew/bundle"
brew "cask"
brew "docker"
brew "gifski"
brew "git"
brew "mas"
brew "mysql"
brew "node"
brew "openjdk@17"
cask "appcleaner"
cask "arc"
cask "cheatsheet"
cask "github"
cask "intellij-idea"
cask "obsidian"
cask "spectacle"
cask "visual-studio-code"
mas "카카오톡", id: 869223134
