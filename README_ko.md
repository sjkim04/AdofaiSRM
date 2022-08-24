# AdofaiSRM
AdofaiSRM은 Twitch 시청자에게 커스텀 레벨을 신청하게 할 수 있는 커스텀 레벨 신청 매니저입니다.

## 설치 방법:
- 최신 릴리스를 [다운로드](https://github.com/thijnmens/AdofaiSRM/releases/latest)합니다
- 모드를 [UnityModManager](https://www.nexusmods.com/site/mods/21)로 설치합니다
  - 설치 방법에 대해서는 [CrackThrough님의 가이드](https://github.com/CrackThrough/ADOFAI-Mod-Installation-Guide/blob/main/kor/use-2.md)를 참조해 주세요
- `AdofaiSRM`를 우클릭하고, `Open Folder`를 선택합니다
  - ![Step 3](https://i.imgur.com/3gC1kSk.png)
- 열린 폴더에 있는 `config.json`(혹은 `config`)을 텍스트 에디터(메모장 등)로 얼어 주세요
  - ![Step 4](https://i.imgur.com/ei1ZZp3.png)
- [https://twitchapps.com/tmi/](https://twitchapps.com/tmi/)로 가 주세요
  - ![Step 5](https://i.imgur.com/LlT0E4u.png)
- `Connect` 버튼을 누르고, Twitch 로그인을 진행해 주세요
- `oauth:`로 시작하는 문자열을 복사해 주세요
  - ![Step 7](https://i.imgur.com/tYdVvdD.png)
- Paste the code you just coppied into the config file under `twitchToken`
- Replace `your channel name here` with your twitch channel name
  - ![Step 8 & 9](https://i.imgur.com/4L71E9e.png)
- Save and close the config
- Validate the config by launching `server.exe` (or just `server`)
  - Does the window close? Than there is still something wrong with your config, double check everything or DM me on discord (`ThiJNmEnS#6669`)
  - Does the window stay open? Well done everything is set up and good to go!

## Usage
#### Streamer
In the `Featured Levels` portal there should be a song called `Song Request Manager`, enter this song and you'll be taken into the request queue

#### Twitch Chat
There are currently 2 command you can use, more are to be added in the future
- `!srm <code>`
  - This command adds a song to the queue, you can use both steam and [adofai.gg](https://adofai.gg/) codes
  - Example Usage
    - !srm 3704
    - !srm gg:3699
    - !srm steam:2804370147
- `!ping`
  - A very basic commands that displays the delay between twitch and the SRM bot
