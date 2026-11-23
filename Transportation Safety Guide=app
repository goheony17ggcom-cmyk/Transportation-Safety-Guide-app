
# 교통수단별 주의사항 리스트
car_attention = [
    "안전벨트를 착용합니다.",
    "창문을 열고 머리를 내밀지 않습니다."
]

bus_attention = [
    "버스가 멈춘 후 승하차합니다.",
    "하차 전 주변 차량을 확인합니다."
]

subway_attention = [
    "열차와 승강장 사이에 주의합니다.",
    "출입문에 기대지 않습니다."
]

# 주의사항 안내 함수
def check_please(road_name, m):

    print("\n-------")
    print("교통수단 탑승 시 주의사항")
    print("이용해 주셔서 감사합니다.")

    if road_name == "차":
        attention = car_attention
    elif road_name == "버스":
        attention = bus_attention
    elif road_name == "지하철":
        attention = subway_attention
    else:
        print("잘못된 교통수단입니다.")
        return

    if m < 500:
        print("안전에 주의하세요!")
    else:
        print("이동 거리가 깁니다. 안전에 더욱 주의하세요!")

    print(road_name + " 이용 시 주의사항")

    for item in attention:
        print("-", item)


# 사용자 입력
road = input("교통수단을 선택하세요 (차/버스/지하철): ")
distance = int(input("이동 거리를 입력하세요(m): "))

# 함수 실행
check_please(road, distance)
