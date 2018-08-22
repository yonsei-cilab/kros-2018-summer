## 제 3회 인공지능 및 로보틱스 여름학교 (8/22,수)

### Codes
- [Lab-01: MLP](https://github.com/yonsei-cilab/kros-2018-summer/tree/master/lab-01-MLP)
- [Lab-02: SVM](https://github.com/yonsei-cilab/kros-2018-summer/tree/master/lab-02-SVM)
- [Lab-03: MLP-tf](https://github.com/yonsei-cilab/kros-2018-summer/tree/master/lab-03-MLP-tf)
- [Lab-04: CNN](https://github.com/yonsei-cilab/kros-2018-summer/tree/master/lab-04-CNN)
- [Lab-05: CNN-tf](https://github.com/yonsei-cilab/kros-2018-summer/tree/master/lab-05-CNN-tf.nn)
- [Lab-06: CNN-tf.layers](https://github.com/yonsei-cilab/kros-2018-summer/tree/master/lab-05-CNN-tf.nn)
- [Lab-07: CNN-tf-slim](https://github.com/yonsei-cilab/kros-2018-summer/tree/master/lab-07-CNN-slim)
- [Lab-08: Object Detection: YOLO](https://github.com/yonsei-cilab/yolo-tensorflow)

### Requirements
- tensorflow
- numpy
- matplotlib
- cvxopt
- scipy
- sklearn 
- opencv-python

#### Package download for Windows + python 3.6
1. [여기](https://drive.google.com/open?id=1k707gyg--Lb_0uTTmBp7_BsllWR8gofH) 에서 .whl 파일 5개 다운로드  
2. win+R -> cmd 를 입력하여 명령 프롬프트 창을 연다.  
3. ``` pip install ".whl파일 다운로드 경로"  ```   
ex) ```pip install "C:\tensorflow-1.10.0-cp36-cp36m-win_amd64.whl"  ```  
위 명령어를 사용하여 tensorflow를 가장 먼저 설치
4. 그 후 나머지 다운받은 4개의 .whl 파일 설치
5. ```pip install scipy  ```
6. ``` pip install sklearn  ```
7. ``` pip install matplotlib  ```

> 기존에 "여기" 에서 다운받으셨던 분들은 .whl 파일 5개가 수정되었으니 다시 다운받아주시고 기존에 설치한 패키지를 아래의 명령어로 모두 삭제해줍니다.  
```pip uninstall numpy tensorflow cvxopt mkl opencv-python```  
그리고 위의 1번부터 다시 설치하시면 됩니다.

#### Package download for Windows + python 3.XX
1. ``` pip install tensorflow  ```
2. ``` pip uninstall numpy  ```   
tensorflow를 설치하며 함께 설치된 기존의 numpy를 삭제해야함
3. https://www.lfd.uci.edu/~gohlke/pythonlibs/#numpy  
위 주소에서 자신에게 맞는 python 버전으로 numpy+mkl 설치  
``` pip install ".whl파일 다운로드 경로"  ```
4. https://www.lfd.uci.edu/~gohlke/pythonlibs/#opencv  
위 주소에서 자신에게 맞는 python 버전으로 opencv 설치  
``` pip install ".whl파일 다운로드 경로"  ```
5. ``` pip install scipy  ```
6. ``` pip install sklearn  ```
7. ``` pip install cvxopt  ```
8. ``` pip install matplotlib  ```  
> tensorflow를 가장 먼저 설치해야 오류가 없습니다. tensorflow를 가장 먼저 설치해주시기 바랍니다.

#### Package download for Ubuntu 16.04
```
$ sudo apt-get install python3-pip python3-dev python-virtualenv python3-numpy python3-tk  
$ sudo pip3 install matplotlib cvxopt scipy sklearn  
$ sudo pip3 install opencv-python tensorflow  
```

### Note
YOLO implementation are simple refactoring of [Peng Zhang's implementation](https://github.com/hizhangp/yolo_tensorflow) for lab.

