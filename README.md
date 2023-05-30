# sass 사용 거의 안 함. scss를 사용한다. scss[사스]

![image](https://github.com/tjghwns93/sass/assets/129016977/5f3fdbe2-2a8f-40dd-af5b-45103ef4c9ad)



# scss 컴파일

![image](https://github.com/tjghwns93/sass/assets/129016977/546517bb-bddc-4e59-8779-139f8752f2a9)


# css 위치변경

![image](https://github.com/tjghwns93/sass/assets/129016977/297c3ea9-c17c-4ae1-ad2c-fb0c923a6e0d)
# savePath:null이면 scss아일과 같은 위치에 style.css가 생긴다
![image](https://github.com/tjghwns93/sass/assets/129016977/877d37fa-4375-447a-9b73-69f9795c7efb)

# ~은 style.css를 의미, /는 style.scss가 있는 폴더
![image](https://github.com/tjghwns93/sass/assets/129016977/f9520753-21a2-474f-a11e-aff2d6e6bd62)

# scss파일이 있는 폴더의 상위요소에 생성
![image](https://github.com/tjghwns93/sass/assets/129016977/3014940d-6e4c-4186-99e8-644ae3dd7edc)

# 주석 처리 방법
# 한 줄 주석은 css로 컴파일 되지 않음.
# 블럭 주석은 css로 컴파일 됨.
![image](https://github.com/tjghwns93/sass/assets/129016977/8e3142e0-fac8-4cef-a7b5-9a555b6e691f)

# 변수 만들기 --> $로 시작함,(영문, 숫자, -, _)만 사용할 수 있음. 숫자로 시작할 수 없음.

![image](https://github.com/tjghwns93/sass/assets/129016977/406850b6-2f7e-441c-b175-3815d8907495)

# Partials(파샬)
--- 관련된 것끼리 묶어서 분리/ 소스에 반복되는 부분들을 분리 분산시켜서 모듈화 시키는 기능

* Partials의 파일명은 _로 시작하며
* 불러들일 때는 @import '파일명' 이 때 파일명에 _는 포함시키지 않고, 확장명도 포함시키지 않는다.

scss는 _로 시작하는 파일은 컴파일하지 않는다
