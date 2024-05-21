## 07-1. 다양한 보조기억장치

- 대중적인 보조기억장치는 하드 디스크와 플래시 메모리가 있다. 플래시 메모리는 USB, SD 카드, SSD와 같은 저장 장치를 말한다.

### 하드 디스크

- 하드 디스크는 자기적인 방식으로 데이터를 저장하는 보조기억장치이다. 따라서 자기 디스크의 일종으로 지칭하기도 한다.

![1_feIxUypplCNxTWvgl4vR9A.webp](https://prod-files-secure.s3.us-west-2.amazonaws.com/ccee4141-ca57-49be-9629-57442a73b9ab/f02e52fe-5e7e-4243-bce2-d4538a8b8736/1_feIxUypplCNxTWvgl4vR9A.webp)

- 플래터: 동그란 원판 모양으로 하드 디스크에서 데이터가 저장되는 곳
    - 플래터는 자기 물질로 덮여 있어 N, S극을 저장하고, 이는 0과 1의 역할을 수행한다.
- 스핀들: 플래터를 회전시키는 구성 요소
    - 스핀들이 플래터를 돌리는 속도는 분당 회전수를 나타내는 RPM 단위로 표현된다.

![1_8QzbRqHIpq1iXBdtnQm0SA.webp](https://prod-files-secure.s3.us-west-2.amazonaws.com/ccee4141-ca57-49be-9629-57442a73b9ab/bfff097c-cd73-425e-9218-20174b401609/1_8QzbRqHIpq1iXBdtnQm0SA.webp)

- 헤드: 플래터를 대상으로 데이터를 읽고 쓰는 구성 요소
- 디스크 암: 헤드를 원하는 위치로 이동시키며, 헤드는 디스크 암에 부착되어 있다.

- 일반적으로 여러 겹의 플래터로 이루어져 있고 플래터 양면을 모두 사용할 수 있다.
- 양면 플래터를 사용하면 위아래로 플래터당 두 개의 헤드가 사용된다.

![1_jqIPMuwighyoEXmryJCOxw.webp](https://prod-files-secure.s3.us-west-2.amazonaws.com/ccee4141-ca57-49be-9629-57442a73b9ab/58ef4880-91d6-4f2a-a676-991db8ef64c4/1_jqIPMuwighyoEXmryJCOxw.webp)

- 플래터는 트랙과 섹터라는 단위로 데이터를 저장한다.
- 섹터는 하드 디스크의 가장 작은 전송 단위이다.
- 여러 겹의 플래터 상에서 같은 트랙이 위치한 곳을 모아 연결한 논리적 단위를 실린더라고 부른다. 연속된 정보는 보통 한 실린더에 기록된다.

![1_0cnZRkpsNuhEogsO2z4JGg.webp](https://prod-files-secure.s3.us-west-2.amazonaws.com/ccee4141-ca57-49be-9629-57442a73b9ab/7f037db3-6dcd-44d0-b4e0-e56307d83644/1_0cnZRkpsNuhEogsO2z4JGg.webp)

- 탐색 시간: 접근하려는 데이터가 저장된 트랙까지 헤드를 이동시키는 시간

  ![1_kC_upr2h0mnxSXQF1eCu4w.webp](https://prod-files-secure.s3.us-west-2.amazonaws.com/ccee4141-ca57-49be-9629-57442a73b9ab/c5af74fd-0584-41b6-90a8-d85bfe4a23e1/1_kC_upr2h0mnxSXQF1eCu4w.webp)

- 회전 지연: 헤드가 있는 곳으로 플래터를 회전시키는 시간

  ![1_UVI6VRVhfesMNNqx-emOsw.webp](https://prod-files-secure.s3.us-west-2.amazonaws.com/ccee4141-ca57-49be-9629-57442a73b9ab/0019e892-bbb2-4b03-957e-cdd57a698ffa/1_UVI6VRVhfesMNNqx-emOsw.webp)

- 전송 시간: 하드 디스크와 컴퓨터 간에 데이터를 전송하는 시간
- 탐색 시간과 회전 지연을 단축시키기 위해서는 플래터를 빨리 돌려 RPM을 높이는 것도 중요하지만, 접근하려는 데이터가 플래터 혹은 헤드를 조금만 옮겨도 접근할 수 있는 곳에 존재하는 것도 중요하다.

### 플래시 메모리

- 전기적으로 데이터를 읽고 쓸 수 있는 반도체 기반의 저장 장치이다.
- 셀: 플래시 메모리에서 데이터를 저장하는 가장 작은 단위
    - 이 셀이 모이고 모여 MB, GB 용량을 갖는 저장 장치가 되는 것이다.
- 하나의 셀에 몇 비트를 저장할 수 있느냐에 따라 종류가 나뉜다.
    - 한 셀에 1비트 저장: SLC
    - 한 셀에 2비트 저장: MLC
    - 한 셀에 3비트 저장: TLC

**SLC 타입**

- 다른 타입에 비해 비트의 빠른 입출력이 가능하고 수명이 길다.
- 하지만 용량 대비 가격이 높다.
- 데이터를 읽고 쓰기가 매우 많이 반복되며 고성능의 빠른 저장 장치가 필요한 경우에 SLC 타입을 사용한다.

**MLC 타입**

- SLC 타입보다 속도와 수명은 떨어지지만 대용량화하기 유리하고 가격이 저렴하다.
- 시중에서 사용되는 많은 플래시 메모리는 MLC 타입 (혹은 TLC 타입)으로 만들어진다.

**TCL 타입**

- 다른 타입보다 수명과 속도가 떨어지지만 용량 대비 가격도 저렴하다.

- 페이지: 셀들이 모여 만들어진 단위
- 블록: 페이지가 모여 만들어진 단위
- 플레인: 블록이 모여 만들어진 단위
- 다이: 플레인이 모여 만들어진 단위
- 플래시 메모리에서 읽기와 쓰기는 페이지 단위로 이루어지고, 삭제는 블록 단위로 이루어진다.
- 페이지는 Free, Valid, Invalid 상태를 가질 수 있다.
    - Free 상태: 어떠한 데이터도 저장하고 있지 않아 새로운 데이터를 저장할 수 있는 상태
    - Valid 상태: 이미 유효한 데이터를 저장하고 있는 상태
    - Invalid 상태: 쓰레기값이라 부르는 유효하지 않은 데이터를 저장하고 있는 상태
- 플래시 메모리는 하드 디스크와는 달리 덮어쓰기가 불가능하여 Valid 상태인 페이지에는 새 데이터를 저장할 수 없다.
- 따라서 쓰레기 값을 저장하고 있는 공간은 사용하지 않을 공간인데도 불구하고 다른 데이터로 바꿀 수 없어 용량을 차지한다.
- 이때 쓰레기값을 정리하기 위해 가비지 컬렉션 기능을 제공한다.

## 07-2. RAID의 정의와 종류

- 1TB 하드 디스크 4개를 동시에 사용하는 것과 4TB 하드 디스크 하나를 사용하는 것 중 뭐가 더 나을까?
- 1TB 하드 디스크 4개로 RAID를 구성하면 더 나은 성능과 안전성이 나타날 수 있다.
- 그렇다면 RAID가 무엇이고 왜 이런 차이가 생길까?

### RAID의 정의

- 데이터의 안전성, 높은 성능을 위해 여러 개의 물리적 보조기억장치를 마치 하나의 논리적 보조기억장치처럼 사용하는 기술이다.

### RAID의 종류

- RAID 구성 방법을 RAID 레벨이라 표현하는데, RAID 0, RAID 1, … RAID 10, RAID 50 등이 있다.

**RAID 0**

- 여러 개의 보조기억장치에 데이터를 단순히 나누어 저장하는 구성방식이다.
- 어떠한 데이터를 저장할 때, 저장되는 데이터가 하드 디스크 개수만큼 나뉘어 저장된다.

  ![1_0rSRxAPZwC0vpEJ4oB3MVA.webp](https://prod-files-secure.s3.us-west-2.amazonaws.com/ccee4141-ca57-49be-9629-57442a73b9ab/73f1330b-d85c-41f4-a8a0-e4e7112c42bb/1_0rSRxAPZwC0vpEJ4oB3MVA.webp)

- 스트라입: 줄무늬처럼 분산되어 저장된 데이터
- 스트라이핑: 분산하여 저장
    - 하나의 대용량 저장 장치를 이용했다면 여러 번에 걸쳐 읽고 써야하지만, 스트라이핑되면 동시에 읽고 쓸 수 있기 때문에 속도가 빨라진다.
- 단점으로는 저장된 정보가 안전하지 않다. 구성된 하드 디스크 중 하나에 문제가 생긴다면 다른 모든 하드 디스크의 정보를 읽는 데 문제가 생길 수 있다.

**RAID 1**

- 복사본을 만드는 방식으로 미러링이라고도 부른다.

  ![1_N5vv0c4nsG3r_BpIYD0tDg.webp](https://prod-files-secure.s3.us-west-2.amazonaws.com/ccee4141-ca57-49be-9629-57442a73b9ab/5f705313-a66a-433e-88e7-977446972da5/1_N5vv0c4nsG3r_BpIYD0tDg.webp)

- 어떠한 데이터를 쓸 때는 원본과 복사본 두 군데에 쓰기 때문에 RAID 0보다 느리다.
- 장점으로는 복구가 매우 간단하다는 점이다.
- 단점으로는 하드 디스크 개수가 한정되었을 때 사용 가능한 용량이 적어지는 점이 있다.

**RAID 4**

![1_n0Wzie5x9a0rbHPBXVWH7Q.webp](https://prod-files-secure.s3.us-west-2.amazonaws.com/ccee4141-ca57-49be-9629-57442a73b9ab/c2e72d0a-57c1-4837-9506-606de6b673f5/1_n0Wzie5x9a0rbHPBXVWH7Q.webp)

- RAID1처럼 완전한 복사본을 만드는 대신 오류를 검출하고 복구하기 위한 정보를 저장한 장치를 두는 구성 방식
- 패리티 비트: 오류를 검출하고 복구하기 위한 정보
    - 패리티를 저장한 장치를 이용해 다른 장치들의 오류를 검출하고, 오류가 있다면 복구한다.

**RAID 5**

![1_PzlE7K9lCVjmoqvlZYr54Q.webp](https://prod-files-secure.s3.us-west-2.amazonaws.com/ccee4141-ca57-49be-9629-57442a73b9ab/cb903252-95de-45d1-8b3a-3e96a41e1d93/1_PzlE7K9lCVjmoqvlZYr54Q.webp)

- RAID4에서는 어떤 새로운 데이터가 저장될 때마다 패리티를 저장하는 디스크에도 데이터를 쓰게되므로 패리티를 저장하는 장치에 병목 현상이 발생한다는 문제가 있다.
- RAID 5는 패리티 정보를 분산하여 저장하는 방식으로 병목 현상을 해결한다.

**RAID6**

![1_NTum2Ue1haslAa2lq1OtZA.webp](https://prod-files-secure.s3.us-west-2.amazonaws.com/ccee4141-ca57-49be-9629-57442a73b9ab/ec6ff954-967d-4980-a3aa-95dee0edff23/1_NTum2Ue1haslAa2lq1OtZA.webp)

- RAID5와 구성은 같지만 서로 다른 두 개의 패리티를 두는 방식이다.
- 쓰기 속도는 RAID 5보다 느리지만 더 안전한 구성이다.