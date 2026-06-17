# notepad-sd
fully dark theme legacy notepad without white flashbang

yeah xp to.. 10<br>100% c/c++ win32api LOL<br>
(c#, uwp, winui is slow & heavy. very bad.)<br><br>
100% owner draw & custom draw LOL (except. Edit Control)<br>


Required minimum OS : Windows 10 1809 x64
<img width="732" height="455" alt="메인" src="https://github.com/user-attachments/assets/61651abf-b8fb-43a4-bfe9-114560be1498" /><br>

100% 다크 테마 레거시 메모장(폰트 선택 다이얼로그의 일부 컨트롤 제외)

창 위치, 폰트 등 Microsoft의 레거시 메모장 설정을 같이 사용합니다.<br>
메모장 종료시 레지스트리에 저장하는 것을 제거해서 항상 같은 창 위치로 실행 됩니다.<br>
메뉴-Settings-Save Settings Now로 저장할 수 있습니다.<br>
Paste Board와 Always On Top의 체크 상태는 저장되지 않습니다.<br><br>
실행후 단축키로 활성화 할 수 있지만, 바로 가기를 만들어<br>
notepad-sd.exe /b<br>
로 Paste Board(텍스트를 복사하면 자동으로 메모장에 붙여넣는 기능)를 활성화한채 실행할 수 있고<br>
notepad-sd.exe /t<br>
로 Always On Top(창 위치를 항상 위에)을 활성화한채로 실행할 수 있습니다.

Word Break를 변경해서 워드워랩과 Ctrl + Left, Ctrl + Right, Ctrl + BackSpace, 더블 클릭으로<br>
선택되는 텍스트가 마이크로소프트 메모장하고 다릅니다.

기존 버그와 윈도우 버그도 몇가지 해결하였고<br>
텍스트 파일의 바로 가기를 드래그 앤 드롭으로 열수 있게 하였습니다.<br><br>

<img width="578" height="316" alt="이전 버전의 Microsoft IME-3r" src="https://github.com/user-attachments/assets/7e2dfa09-4cca-43f3-8b69-c5a2d5f23c71" /><br>
일본어 등도 그런지 모르겠지만, 한글 Windows 11 사용자는 IME버그 때문에<br>
윈도우 설정에서 '이전 버전의 Microsoft IME사용'을 활성화해야<br>
텍스트 입력시 마지막 글자가 사라지거나 Edit컨트롤이 멈추는 현상이 사라집니다.<br><br>

<img width="1019" height="613" alt="FileDialog-WhiteFlashBang" src="https://github.com/user-attachments/assets/208fc893-78a2-457d-9c84-67aeefc50a9b" /><br>

<img width="788" height="607" alt="TaskMgr-WhiteFlashBang" src="https://github.com/user-attachments/assets/f585a42f-3e77-4600-894c-8e623fc23920" /><br>


notepad-sd는 흰색 번쩍임이 없지만,<br>
파일 다이얼로그는 흰색으로 번쩍이는데, 이는 윈도우 소유라서<br>
릴리즈에 있는 <br>ColorChange-WhiteFlashBang.reg를 등록하여<br>
윈도우 컬러를 회색으로 변경하는걸로 완화할 수 있습니다.<br><br>
(레지스트리 HKEY_CURRENT_USER\Control Panel\Colors의 Window 밸류)<br>
(작업관리자 등, Windows 전체에 적용 됨. Windows 11 25H2 26200.7462기준)<br>
(검은색으로 하면 윈도우 일반 Edit컨트롤의 글자 색상 때문에 알아볼수 없게 됩니다)<br>
(나중에 마이크로소프트가 윈도우 업데이트로 해결할 가능성이 있습니다)<br>

<img width="646" height="745" alt="RegEdit-WhiteFlashBang" src="https://github.com/user-attachments/assets/3ad0f937-4593-4a69-a9a4-69fe089363e6" />
<br>
<img width="1018" height="400" alt="FontDialog-WhiteTextBG" src="https://github.com/user-attachments/assets/7d7a3a2a-b281-4c0c-8488-66d15c00c629" /><br>

<br><br>



<img width="612" height="182" alt="overwrite" src="https://github.com/user-attachments/assets/e1651f75-abb4-4fae-a93e-9166998adadb" />
<br>
파일 다이얼로그의 덮어쓰기 확인 창, 읽기 전용 파일 안내 창도 다크 테마로 만들었지만<br>
텍스트가 나라별 언어와 일치하지 않아서 미적용.<br><br><br>

<img width="906" height="150" alt="InActiveCaptionBar" src="https://github.com/user-attachments/assets/2c8fb947-7513-4902-bb7a-0e983a243e79" />
<br>
Windows 11에서는 비활성 창의 타이틀바 컬러가 다크 테마가 아니라서<br>
릴리즈의 <br>ColorChange-InActiveCaptionBar-forWindows11.reg를 등록하여 어두운 색으로 변경할 수 있습니다.<br>
(Windows 전체에 적용 됨. Windows 10에서는 정상)<br><br><br>

<img width="233" height="181" alt="시스템메뉴" src="https://github.com/user-attachments/assets/327a137a-e6bb-48ba-950b-eb6c0ea6f7c2" /><br>
시스템 메뉴 아이콘은 가볍게 읽어 올수 있는걸로 사용.<br>
