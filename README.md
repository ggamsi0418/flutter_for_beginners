# ๐ Flutter๋ก ์นํฐ ์ฑ ๋ง๋ค๊ธฐ

## ๋ง๋ค์ด ๋ณธ ๊ฒ

### 1. Mobile Wallet(UI)

<img width="80%" src="https://user-images.githubusercontent.com/58096698/210097126-a7f6ed47-e191-413d-91d9-c9c0e1b666c0.png"></img>

### 2. Pomodoro App

<img height="500" src="https://user-images.githubusercontent.com/58096698/210199646-7cd84afa-f6c1-4056-9c22-0d5ada6a6170.gif"></img>

### 3. Webtoon App

<img height="500" src="https://user-images.githubusercontent.com/58096698/210821427-79560c11-d4e8-4792-a837-d53c4b7af5f0.gif"></img>

## โ ํ๊ฒฝ ์ธํ (Windows10 ๊ธฐ์ค) โ

### 1. Flutter ๋ฒ์  ๊ด๋ฆฌ ๋งค๋์  ์ค์น

- ์๋์ฐ์์๋ `asdf`๋ฅผ ์ด์ฉํ  ์ ์์ด `fvm`์ ์ฌ์ฉํ๊ธฐ๋ก ๊ฒฐ์ 
- choco๋ฅผ ์ด์ฉํ์ฌ ์ค์น
  ```shell
  $ choco install fvm
  ```
- ๋ช๋ น์ด

  ```shell
  $ fvm releases # ์๊ฒฉ ์ ์ฅ์๋ก๋ถํฐ ์ค์น ๊ฐ๋ฅํ sdk ๋ฒ์  ํ์ธ
  $ fvm install <version> # ํน์  ๋ฒ์  ์๋ ฅํ์ฌ ์ค์น. 3.3.10 ์ค์น
  $ fvm use 3.3.10 # ํ๋ก์ ํธ ๋ด์์ ์ฌ์ฉํ  Flutter ๋ฒ์ ์ ์ง์  -> .fvm ํด๋ ์๊น
  ```

- ์ดํ ํฐ๋ฏธ๋์์ flutter ๋๋ dart ๋ช๋ น์ด๋ฅผ ์ฌ์ฉํ  ๋๋ ํญ์ ์์ `fvm`์ ๋ถ์ฌ์ผ ํ๋ค.

  ```shell
  # ์์

  $ fvm flutter --version
  $ fvm flutter run main.dart
  ```

- ์ฐธ๊ณ 
  - https://fvm.app/docs/getting_started/installation
  - https://velog.io/@knh4300/fvm

### 2. ๋น์ฅฌ์ผ ์คํ๋์ค ์ค์น

- Flutter์์ Windows ๋ฐ์คํฌํฑ ์ฑ์ผ๋ก ๋น๋ํ  ๋ ํ์
- ๋ค์ ๋งํฌ์์ Visual Studio 2022 ๋ค์ด๋ก๋ ํ ์ค์น
  - https://visualstudio.microsoft.com/ko/downloads/
  - `C++๋ฅผ ์ฌ์ฉํ ๋ฐ์คํฌํฑ ๊ฐ๋ฐ` ์ ํ ํ ์ค์น

### 3. ์๋๋ก์ด๋ ์คํ๋์ค ์ค์น ๋ฐ VDM ๊ตฌ์ฑ

- ์๋๋ก์ด๋ ์คํ๋์ค ๋ค์ด๋ก๋ ํ ์ค์น
  - https://developer.android.com/studio?hl=ko
- ๊ธฐ๋ณธ์ ์ธ ์ค์น๊ฐ ์๋ฃ๋๋ฉด `SDK Manager`๋ฅผ ํตํด ํ์ํ tool๋ค์ ์ค์น
- ์๋์ฐ `์์คํ ํ๊ฒฝ ๋ณ์ ํธ์ง`์์ ํ๊ฒฝ ๋ณ์ ์ถ๊ฐ
- VDM์์ ์๋ฎฌ๋ ์ดํฐ ์ถ๊ฐ
- ์ฐธ๊ณ 
  - https://velog.io/@completed1991/%EC%95%88%EB%93%9C%EB%A1%9C%EC%9D%B4%EB%93%9C-%EC%8A%A4%ED%8A%9C%EB%94%94%EC%98%A4-%EC%84%A4%EC%B9%98-%EB%B0%8F-%ED%99%98%EA%B2%BD%EB%B3%80%EC%88%98-%EC%85%8B%ED%8C%85
  - https://velog.io/@qkrtnfks128/Flutter%EC%8B%9C%EC%9E%91%ED%95%98%EA%B8%B0%EC%9C%88%EB%8F%84%EC%9A%B0
  - https://fre2-dom.tistory.com/175

### 4. Flutter ์ค๋น ์ํ ํ์ธ

- ![image](https://user-images.githubusercontent.com/58096698/210065024-f2a437a2-acac-48fb-b8b8-de503b157dcf.png)

## โ ํ๊ฒฝ ์ธํ (WSL2 ๊ธฐ์ค, ์๋๋ก์ด๋ ์๋ฎฌ๋ ์ดํฐ ์ฐ๋ ๋ถ๊ฐ) โ

<details>
<summary>์์ธ ๋ณด๊ธฐ</summary>

### [์ฌ์ ์ค๋น] asdf(๋ฒ์  ๊ด๋ฆฌ ๋งค๋์ ) ๋ฐ flutter ์ค์น ๋ฐฉ๋ฒ

- ์ฐธ๊ณ : https://github.com/ggamsi0418/dart-for-beginners#readme

### 1. ๊ตฌ๊ธ ์ค์ 

- `Ubuntu(wsl2)` ๋ด์ `ํฌ๋กฌ`์ ์ค์นํ๋ค.
  ![image](https://user-images.githubusercontent.com/58096698/209977325-b0e60494-bb52-4acf-af16-ec6406397e23.png)

- `.zshrc` ํ์ผ์ ํฌ๋กฌ ์คํ ๊ฒฝ๋ก๋ฅผ ์ถ๊ฐํ๋ค.
  ```bash
  # Chrome path
  export CHROME_EXECUTABLE=/opt/google/chrome/chrome
  ```

### 2. ์๋๋ก์ด๋ ์คํ๋์ค ์ค์น (`์๋ฎฌ๋ ์ดํฐ ๊ตฌ์ฑ ๋ถ๊ฐ`)

```
์๋ฎฌ๋ ์ดํฐ ์ฌ์ฉ์ด ๋ถ๊ฐํ๋ฏ๋ก ์๋๋ก์ด๋ ์คํ๋์ค ์ค์น๋ ํ์x
```

- ํ ๋๋ ํ ๋ฆฌ(~/ or $HOME)์ `Application ํด๋` ์์ฑ ํ ์ด๋

  ```shell
  $ mkdir ~/Application && cd ~/Application
  ```

- ์๋๋ก์ดํธ ์คํ๋์ค(Linux) ๋ค์ด๋ก๋
  ```shell
  $ get https://redirector.gvt1.com/edgedl/android/studio/ide-zips/2021.3.1.17/android-studio-2021.3.1.17-linux.tar.gz
  ```
- ์์ถ ํด์ (= ์ค์น)
  ```shell
  $ tar -xvf android-studio-2021.3.1.17-linux.tar.gz
  ```
- ์๋๋ก์ด๋ ์คํ๋์ค ์คํ
  ```shell
  $ sh ~/Applications/android-studio/bin/studio.sh
  ```
- ๊ธฐ๋ณธ ์ค์น ํ SDK TOOL์์ ์ถ๊ฐ ์ค์น
  ![image](https://user-images.githubusercontent.com/58096698/209960909-b03ffbcb-5d40-4a0c-91ad-82bb9f299783.png)

- ํ๋ก์ ํธ ํด๋๋ก ์ด๋ํ์ฌ flutter์ ์๋๋ก์ด๋ ์คํ๋์ค ์ฐ๋

  ```shell
  $ cd ~/Workspace/nomad-coders/flutter-for-beginners
  $ flutter config --android-sdk $HOME/Android/Sdk
  $ flutter config --android-studio-dir $HOME/Applications/android-studio/
  ```

- ์๋๋ก์ด๋ ์คํ๋์ค ๋ผ์ด์ผ์ค ์ถ๊ฐ ์ค์ 

  ```shell
  $ flutter doctor --android-licenses
  ```

- ๋ง์ง๋ง์ผ๋ก ์ต์ข ํ์ธ

  ```shell
  $ flutter doctor -v
  ```

  ![image](https://user-images.githubusercontent.com/58096698/209958812-2e6fc832-5ad4-4b0d-99fc-e1cde4cf8c83.png)

- ์ฐธ๊ณ : https://addshore.com/2022/01/installing-android-studio-on-wsl2-for-flutter/

</details>
