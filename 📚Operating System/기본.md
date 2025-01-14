--------------- 기본 양식 ----------------

<details>
<summary>❓</summary>

>""

</details>

------------------------------------------

<details>
<summary>❓프로그램이 실행되려면 무엇이 필요할까</summary>

>"모든 프로그램은 하드웨어를 필요로 한다. 예를 들어 덧셈 프로그램은 CPU를 필요로 하고, 이미지를 저장하는 프로그램은 하드디스크를 필요로 한다."

</details>

<details>
<summary>❓운영체제(Operating System)란</summary>

>"실행할 프로그램에 필요한 자원을 할당하고, 프로그램이 올바르게 실행되도록 돕는 특별한 프로그램"

</details>

<details>
<summary>❓시스템 자원의 개념</summary>

>"프로그램을 실행에 마땅히 필요한 요소들을 가리켜서 시스템 자원 혹은 자원이라고 한다. 예를 들면, CPU, 메모리, 보조기억장치, 입출력장치 등의 컴퓨터 부품들이 해당된다."

</details>

<details>
<summary>❓운영체제는 언제 어떻게 실행되는가?</summary>

>"운영체제는 컴퓨터가 부팅될 때 메모리 내의 커널 영역(kernel space)에 따로 적재되어 실행된다."
![image](https://github.com/user-attachments/assets/996af355-986f-44c9-9876-9fd472684eaf)

</details>

<details>
<summary>❓사용자 영역이란?</summary>

>"커널 영역을 제외한 나머지 영역, 즉 사용자가 이용하는 응용 프로그램이 적재되는 영역을 사용자 영역(user space)이라고 한다."

</details>

<details>
<summary>❓운영체제의 역할</summary>

>"실행할 프로그램을 메모리에 적재하고, 필요없는 프로그램은 메모리에서 삭제하며 메모리 자원을 지속적으로 관리한다. 또한 실행시 CPU 자원을 관리하고 할당한다. "
![image](https://github.com/user-attachments/assets/d1c4032f-c831-4215-adb2-f55bd241b251)
![image](https://github.com/user-attachments/assets/56f50c04-a76b-4991-8c1f-7d6ac5789952)

</details>

<details>
<summary>❓운영체제를 알아야 하는 이유</summary>

>"프로그램은 결국 하드웨어가 실행하고, 하드웨어를 조작하는 프로그램이 운영체제이기 때문에 ( 하드웨어에 대한 이해 및 문제 해결능력 ) 오류 메시지와 같은 것들을 이해하기 위해서"

</details>

<details>
<summary>❓운영체제의 커널(kernel)이란?</summary>

>"자원에 접근 및 조작, 프로그램의 올바른 실행 등의 운영체제의 핵심 서비스를 담당하는 부분을 커널이라고 한다."
![image](https://github.com/user-attachments/assets/d3da51cf-a060-4c11-a189-070c1991f84d)

</details>

<details>
<summary>❓사용자 인터페이스의 개념</summary>

>"사용자 인터페이스(UI;User Interface)란 사용자가 컴퓨터와 상호작용할 수 있는 통로를 말한다. 커널에는 포함되지 않는 서비스이다."

</details>

<details>
<summary>❓운영체제가 제공하는 사용자 인터페이스 2가지</summary>

>"운영체제가 제공하는 사용자 인터페이스의 종류에는 그래픽 유저 인터페이스(GUI; Graphical User Interface)와 커맨드 라인 인터페이스(CLI; Command Line Interface)가 있다."

</details>

<details>
<summary>❓GUI와 CLI의 차이</summary>

>"GUI는 그래픽을 기반으로 컴퓨터와 상호작용할 수 있는 인터페이스이고, CLI는 명령어를 기반으로 컴퓨터와 상호작용할 수 있는 인터페이스이다."

</details>

<details>
<summary>❓응용프로그램 및 하드웨어 관점에서 운영체제의 역할</summary>

>"운영체제는 사용자가 실행하는 프로그램이 하드웨어 자원에 직접 접근하는 것을 방지하여 자원을 보호한다. 운영체제 코드 실행을 통해서만 자원에 접근하여 요청 작업 수행이 가능하다."
>![image](https://github.com/user-attachments/assets/8dbadb44-7bca-4074-8d08-279b1fe5b20e)
![image](https://github.com/user-attachments/assets/bc1d0571-e576-4386-9bee-a8b310c677c4)

</details>

<details>
<summary>❓이중 모드의 개념</summary>

>"이중 모드(dual mode)는 CPU가 명령어를 실행하는 모드를 크게 사용자 모드와 커널 모드로 구분하는 방식이다."
![image](https://github.com/user-attachments/assets/c2b7d29b-a4ee-410b-8f0d-47cd980924e9)

</details>

<details>
<summary>❓사용자 모드(user mode)의 개념</summary>

>"운영체제 서비스를 제공받을 수 없는 실행 모드, 즉 커널 영역의 코드를 실행할 수 없는 모드이다. ( 일반적인 응용 프로그램에 해당 )"

</details>

<details>
<summary>❓커널 모드(kernel mode)의 개념</summary>

>"운영체제 서비스를 제공받을 수 있는 실행 모드로, 커널 영역의 코드를 실행할 수 있는 모드이다. ( 운영체제에 해당 ) "

</details>

<details>
<summary>❓시스템 호출(System call)의 개념</summary>

>"사용자 모드로 실행되는 프로그램이 운영체제 서비스를 제공받기 위한 요청을 말한다. ( 커널 모드로 전환하는 방법 )"
![image](https://github.com/user-attachments/assets/6e7020e7-3a73-4f7a-91c5-7e05fd14c67e)

</details>

<details>
<summary>❓인터럽트의 개념</summary>

>"CPU에게 Mode bit가 0(커널 모드)으로 변경 됨을 알리는 신호를 말한다."

</details>

<details>
<summary>❓소프트웨어 인터럽트의 개념</summary>

>"특정한 명령어에 의해 발생하는 소프트웨어적인 인터럽트"
![image](https://github.com/user-attachments/assets/914045d3-345b-47c3-b9be-53930e6d073f)

</details>

<details>
<summary>❓일반적인 응용 프로그램의 동작 과정</summary>

>"빈번한 시스템 호출을 발생시키면서 사용자 모드와 커널 모드를 오가며 실행된다."
![image](https://github.com/user-attachments/assets/4e69a040-9974-426c-9b1b-3c51b4958ebe)

</details>

<details>
<summary>❓프로세스의 개념</summary>

>"프로세스(process)란 실행 중인 프로그램을 말한다."

</details>

<details>
<summary>❓CPU의 프로세스 처리</summary>

>"일반적으로 하나의 CPU는 한 번에 하나의 프로세스만 실행할 수 있어서, CPU는 프로세스들을 조금씩 번갈아 가며 실행한다."
![image](https://github.com/user-attachments/assets/a0c16e87-b0f9-4ea0-a82c-3ddf2c044d25)

</details>

<details>
<summary>❓모든 프로세스의 실행에 있어 필수적인 요소</summary>

>"자원이 필요하다. CPU, 메모리, 입출력장치, 보조기억장치 등..."

</details>

<details>
<summary>❓CPU 스케줄링의 개념</summary>

>"일반적으로 메모리에는 여러 프로세스가 적재되는 반면, 하나의 CPU는 한 번에 하나의 프로세스만 실행할 수 있다. 운영체제가 프로세스들에 공정하게 CPU를 할당하기 위한 방법을 CPU 스케줄링이라 한다."

</details>

<details>
<summary>❓인터럽트 서비스 루틴의 개념</summary>

>"커널 영역에 있는 인터럽트를 처리하는 프로그램을 말한다. 인터럽트를 처리하는 커널 함수이다."

</details>

<details>
<summary>❓가상 머신(virtual machine)의 개념</summary>

>"소프트웨어적으로 만들어낸 가상 컴퓨터를 말한다. 가상 머신을 통해 새로운 운영체제와 응용 프로그램 설치 및 실행이 가능하다."

</details>

<details>
<summary>❓하이퍼바이저의 개념</summary>

>"물리적인 하드웨어와 가상 머신의 영역을 분리하고 자신이 그 사이에서 중간 관리자, 즉 인터페이스 역할을 하는 소프트웨어"

</details>
