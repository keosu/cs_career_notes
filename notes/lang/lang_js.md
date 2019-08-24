  
  
# ��������   
  
### Number  
JavaScript�����������͸�������ͳһ��Number��ʾ�����¶��ǺϷ���Number���ͣ�  
```  
  123; // ����123  
  0.456; // ������0.456  
  1.2345e3; // ��ѧ��������ʾ1.2345x1000����ͬ��1234.5  
  -99; // ����  
  NaN; // NaN��ʾNot a Number�����޷�������ʱ��NaN��ʾ  
  Infinity; // Infinity��ʾ���޴�   
```   
  Number����ֱ�����������㣬�������ѧһ�£�  
```    
  1 + 2; // 3  
  (1 + 2) * 5 / 2; // 7.5  
  2 / 0; // Infinity  
  0 / 0; // NaN  
  10 % 3; // 1  
  10.5 % 3; // 1.5   
```

### �ַ���  
�ַ������Ե�����'��˫����"�������������ı�������'abc'��"xyz"�ȵȡ�   
  
### ����ֵ  
����ֵ�Ͳ��������ı�ʾ��ȫһ�£�һ������ֵֻ��true��false����ֵ  
  
**�Ƚ������**  
  
��һ����==�Ƚϣ������Զ�ת�����������ٱȽϣ��ܶ�ʱ�򣬻�õ��ǳ�����Ľ����  
  
�ڶ�����===�Ƚϣ��������Զ�ת���������ͣ�����������Ͳ�һ�£�����false�����һ�£��ٱȽϡ�  
  
����JavaScript������ȱ�ݣ���Ҫʹ��==�Ƚϣ�ʼ�ռ��ʹ��===�Ƚϡ�  
  
��һ��������NaN��������Number����������ֵ������ȣ��������Լ���  
  
NaN === NaN; // false�� Ψһ���ж�NaN�ķ�����ͨ��isNaN()������  
  
isNaN(NaN); // true  


**null��undefined**  
null��ʾһ�����ա���ֵ������0�Լ����ַ���''��ͬ��0��һ����ֵ��''��ʾ����Ϊ0���ַ�������null��ʾ���ա���  
  
�����������У�Ҳ������JavaScript��null�ı�ʾ������JavaҲ��null��Swift��nil��Python��None��ʾ�����ǣ���JavaScript�У�����һ����null���Ƶ�undefined������ʾ��δ���塱��  
  
JavaScript�������ϣ����null��ʾһ���յ�ֵ����undefined��ʾֵδ���塣���������£����Ƕ�Ӧ����null��undefined�������жϺ��������Ƿ񴫵ݵ���������á�  
  
### ����  
�����ĸ�������Ϻͳ��д����ķ��̱�����һ�µģ�ֻ���ڼ���������У������������������֣��������������������͡�  
  
������JavaScript�о�����һ����������ʾ���������Ǵ�СдӢ�ġ����֡�$��_����ϣ��Ҳ��������ֿ�ͷ��������Ҳ������JavaScript�Ĺؼ��֣���if��while�ȡ�����һ��������var��䣬���磺  
```  
var a; // �����˱���a����ʱa��ֵΪundefined  
var $b = 1; // �����˱���$b��ͬʱ��$b��ֵ����ʱ$b��ֵΪ1  
var s_007 = '007'; // s_007��һ���ַ���  
var Answer = true; // Answer��һ������ֵtrue  
var t = null; // t��ֵ��null   
```  
��JavaScript�У�ʹ�õȺ�=�Ա������и�ֵ�����԰������������͸�ֵ��������ͬһ���������Է�����ֵ�����ҿ����ǲ�ͬ���͵ı���������Ҫע��ֻ����var����һ�Σ����磺  
   
  
### strictģʽ  
JavaScript�����֮����Ϊ�˷����ѧ��ѧϰ������ǿ��Ҫ����var���������������ƴ�����������صĺ�������һ������û��ͨ��var�����ͱ�ʹ�ã���ô�ñ������Զ�������Ϊȫ�ֱ�����   
  
ʹ��var�����ı�������ȫ�ֱ��������ķ�Χ�������ڸñ����������ĺ������ڣ������ĸ���Ժ󽲽⣩��ͬ�������ڲ�ͬ�ĺ������ڻ�����ͻ��  
  
Ϊ���޲�JavaScript��һ�������ȱ�ݣ�ECMA�ں����淶���Ƴ���strictģʽ����strictģʽ�����е�JavaScript���룬ǿ��ͨ��var����������δʹ��var����������ʹ�õģ����������д���  
  
����strictģʽ�ķ�������JavaScript����ĵ�һ��д�ϣ�  
  
'use strict';  

## ������

- ȫ��
- �ֲ�(�������ã�ʹ�� var����)
- �鼶������( ES6����, let�����������б�������)

# javascript ���ö���

JavaScript�Ķ�����һ���ɼ�-ֵ��ɵ����򼯺ϣ����磺  
```JavaScript  
var person = {  
    name: 'Bob',  
    age: 20,  
    tags: ['js', 'web', 'mobile'],  
    city: 'Beijing',  
    hasCar: true,  
    zipcode: null  
};  
```
JavaScript����ļ������ַ������ͣ�ֵ�����������������͡�   
  
Ҫ��ȡһ����������ԣ������ö������.�������ķ�ʽ��  
  
person.name; // 'Bob'  
person.zipcode; // null  
'name' in person // true

## Array
���飬���԰��������������ͣ���ͨ������������ÿ��Ԫ�أ����ȷ���length����
> new Array(1, 2, 3); // ����������[1, 2, 3], ����ֱ��ʹ��[]�� 

�����Ԫ�ؿ���ͨ�����������ʡ���ע�⣬��������ʼֵΪ0��  
  
var arr = [1, 2, 3.14, 'Hello', null, true];  
arr[0]; // ��������Ϊ0��Ԫ�أ���1  
arr[5]; // ��������Ϊ5��Ԫ�أ���true  
arr[6]; // ���������˷�Χ������undefined  

- concat()
- indexOf()
- join()
- lastIndexOf()
- pop()
- push()
- reverse()
- shift()
- slice()
- sort()
- splice()
- toString()
- unshift()
- valueOf()

## String 
�ַ���������''��""���������ַ���ʾ��

- charAt()
- charCodeAt()
- concat()
- fromCharCode()
- indexOf()
- lastIndexOf()
- match()
- replace()
- search()
- slice()
- split()
- substr()
- substring()
- toLowerCase()
- toUpperCase()
- valueOf()

## Map
  
�����еļ���ֵ�������κ����͡����ʹ��������Կ�򼯺����ֵ������ֵ���滻��ֵ��  
> var mp = new Map();  
  
- clear	  ��ӳ�����Ƴ�����Ԫ�ء�  
- delete	  ��ӳ�����Ƴ�ָ����Ԫ�ء�  
- forEach ��ӳ���е�ÿ��Ԫ��ִ��ָ��������   
- get	  ����ӳ���е�ָ��Ԫ�ء�  
- has	  ���ӳ�����ָ��Ԫ�أ��򷵻� true��  
- set	  ���һ���½�Ԫ�ص�ӳ�䡣  
- toString	  ����ӳ����ַ�����ʾ��ʽ��  
- valueOf	  ����ָ�������ԭʼֵ��

## Set
Set��Map���ƣ�Ҳ��һ��key�ļ��ϣ������洢value������key�����ظ������ԣ���Set�У�û���ظ���key��

# ����

���庯��

```Javascript
function abs(x) {
    if (x >= 0) {
        return x;
    } else {
        return -x;
    }
}
```


## �߽׺���(Higher-order function)

һ�������Ϳ��Խ�����һ��������Ϊ���������ֺ����ͳ�֮Ϊ�߽׺�����

```Javascript 
function add(x, y, f) {
    return f(x) + f(y);
}
add(-5, 6, Math.abs)
```

## �հ�(Closure)

�հ�����Я��״̬�ĺ�������������״̬������ȫ������������,���Է�װ˽�б���
```javascript
function create_counter(initial) {
    var x = initial || 0;
    return {
        inc: function () {
            x += 1;
            return x;
        }
    }
} 

var c1 = create_counter();
c1.inc(); // 1
c1.inc(); // 2
c1.inc(); // 3

var c2 = create_counter(10);
c2.inc(); // 11
c2.inc(); // 12
c2.inc(); // 13
```
## ��ͷ����(Arrow Function)
��ͷ�����൱���������������Ҽ��˺�������
```javascript
// ��������:
(x, y) => x * x + y * y

// �޲���:
() => 3.14

// �ɱ����:
(x, y, ...rest) => {
    var i, sum = x + y;
    for (i=0; i<rest.length; i++) {
        sum += rest[i];
    }
    return sum;
}
```