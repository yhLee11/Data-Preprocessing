# Data-Preprocessing; 졸업프로젝트용 데이터 처리 모듈
## ImgClassification.py
- 대용량의 이미지 데이터 검수용 프로그램
### [keyboard]
1. d: delete image (save to delimg.txt)
2. k: edit image (save to editimg.txt)
3. n: next image
4. z: stop!
### [file]
1. del_f: delete file number list
2. edit_f: edit file number list
3. current_r_ptr: current file number pointer for read
4. current_w_ptr: current file number pointer for write

## add_cls_num_1031.py
- add class number to original coordinates txt file
- (ex) 2 5 410 415 -> 1 2 5 410 415

## changeClsNumwith_darknet.py
- 폴더 이름을 기준으로 cls_num 변경

## downloadImgfromURL.py
- 스토리지에 저장된 이미지의 URL로 부터 이미지 다운로드
- URL 문자열을 파싱하여 이름으로 지정 후 저장

## xml_parser.py
- xml 형식의 파일에서 바운딩박스 정보 추출 후 텍스트 파일로 
