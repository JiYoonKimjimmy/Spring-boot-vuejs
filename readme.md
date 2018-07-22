# Spring boot - Vue.js �����ϱ�

Spring boot�� Vue.js�� ������ ������ ������Ʈ�Դϴ�.  
���� ������ ���ʿ� --> <http://febdy.tistory.com/65>


### Version  
Spring boot 2.0.3  
vue.js 2.5.16  
Webpack 3.12.0  
gradle 4.x  
  
  
  

### ���� ����

project  
��  
�� src  
���� main  
�������� java  
�������� resources  
���� test  
��  
�� frontend  
���� build  
���� config  
���� node_modules  
����  src  
�������� assets  
�������� router  
�������� shared-components  
�������� spa  
�������� App.vue  
�������� main.js  
����  
���� static  
���� test  
���� .bablerc  
���� .editorconfig  
���� .eslintingore  
���� .eslintrc.js  
���� index.html  
���� package.json  
���� package-lock.json  
��  
�� build.gradle  
�� gradlew  
�� gradlew.bat  
�� settings.gradle  


frontend ���� ���� : <https://github.com/vuejs-kr/vuejs-kr.github.io/issues/28>


### STEP
#### 1. node.js ��ġ  
<https://nodejs.org/ko/>  
����(180718) ���� 8.11.3 LTS ��ġ��.  

#### 2. install
```
$ cd frontend  
$ npm install
```

#### 3. build
```
$ npm run build
```

#### 4. run
spring boot server run  

#### 5. localhost:8888/hi ���� Ȯ��.  