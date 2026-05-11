# Simple Reflex Roomba

Mo phong Simple Reflex Agent cho robot hut bui tu dong bang Python.

## Yeu cau
- Python >= 3.10
- Tested on Python 3.14.2
- Jupyter Notebook hoac PyCharm

## Cach chay
Mo file `.ipynb`, chay tung cell theo thu tu:
1. Chay Cell 1
   - Nhap so hang va cot
   - Nhap gia tri tung o theo tung hang

2. Chay Cell 2
   - Xem danh sach o hop le
   - Nhap vi tri bat dau robot (vi du: 0 1)

3. Chay Cell 3
   - Nhap so buoc toi da
   - Xem agent chay tung buoc

Neu muon thu lai:
   - Chi can chay lai Cell 3 (room tu dong reset ve ban dau)
   - Neu muon doi room: chay lai tu Cell 1

## Mo ta
- Cell 1: Nhap room, kich thuoc va gia tri tung o
- Cell 2: Cau hinh rules, chon vi tri robot
- Cell 3: Chay agent tu dong

## Quy uoc
| Gia tri | Y nghia   |
|---------|-----------|
| 0       | O sach    |
| 1,2,3   | O ban     |
| -1      | Vat can   |
| R       | Robot     |