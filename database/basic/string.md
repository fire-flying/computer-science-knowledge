## 字符串函数

### 1. 截断字符串

#### 1.1 SUBSTRING_INDEX

#### 1.2 SUBSTR

### 2. 获取字符串位置

#### 2.1 LOCATE(substr,str) 

#### 2.2 POSITION(substr IN str) 

### 3. 拼接字符串

#### 3.1 CONCAT()

``` sql
SELECT CONCAT(userName, ': ', phoneNumber) AS userInfo FROM users;
```