## Main feature

1. **Crop id card and avatar from image**
2. **Show infomation about student in id card**

## Demo

1. Image post to api /upload:

![alt text](https://github.com/manhtung001/student-ID-PTIT-OCR/blob/main/readmeUtils/origin.jpg?raw=true)

Result from backend:

![alt text](https://github.com/manhtung001/student-ID-PTIT-OCR/blob/main/readmeUtils/result.jpg?raw=true)

2. Response from api /upload:
```
{
  "result": {
    "Lớp": "D17CQPTO2-B",
    "id": "B17DCPTO22",
    "Ngành": "CN ĐPT",
    "HỆ": "ĐHCQ",
    "Họ và tên": "Phùng Thị Ngọc Ánh",
    "Sinh ngày": "02/12/1999",
    "Hộ khẩu TT": "H. Thạch Thất - Hà Nội",
    "Khóa": "2017-2022"
  }
}
```

3.1. Response from api get /avatar:

![alt text](https://github.com/manhtung001/student-ID-PTIT-OCR/blob/main/readmeUtils/avatar.jpg?raw=true)

3.2. Response from api get /card:

![alt text](https://github.com/manhtung001/student-ID-PTIT-OCR/blob/main/readmeUtils/card.jpg?raw=true)

## How to test this app

### Requirements

```
Python 3.7
Pip 21.3.1
```

### Instructions

**0. Clone the folder app**

```sh
git clone https://github.com/manhtung001/student-ID-PTIT-OCR.git
```

**1. Download weight vietocr**

```sh
download from: https://drive.google.com/uc?id=13327Y1tz1ohsm5YZMyXVMPIOjoOA0OaA
move file transformerocr.pth to folder student-ID-PTIT-OCR/
```

**2. Install python package**

```sh
pip install -r requirements.txt
```

**3. Run api**

```sh
python api.py
```
