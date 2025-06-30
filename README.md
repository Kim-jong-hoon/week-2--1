# week-2--1
<colab 시험>

1번문제
![df](https://github.com/user-attachments/assets/c914dd29-85ea-4c7f-b96e-c78f2f66396a)




sensors = {
    "front": 8.0,   
    "left": 15.0,   
    "right": 4.0  
}


safe_distance = 10.0


obstacles = []


for direction, distance in sensors.items():
    if distance < safe_distance:
        # 안전 거리보다 가까우면 장애물로 간주하고 추가
        obstacles.append(direction)


if obstacles:
    print("장애물 발견된 위치:", obstacles)
else:
    print("장애물 없음")



2번 문제
![스크린샷_30-6-2025_94753_claude ai](https://github.com/user-attachments/assets/baad1ca3-1d82-434a-a4ce-15cbf08a319a)


3번 문제

![스크린샷_30-6-2025_95346_claude ai](https://github.com/user-attachments/assets/b4b72fbe-fec1-43ad-abab-12dfeb0f252a)
