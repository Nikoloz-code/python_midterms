# Mutable
მუტაბელური (Mutable) ობიექტები პითონში არის ისეთი ობიექტები, რომლების დარედაქტირება
შეიძლება იმის შემდეგ როდესაც იგი შევქმენით. მაგალითად Set და Dictionary:

```python
listObject = [1,2,3] #Create a list
dictionaryObject = {} #Create a Dictionary

listObject.append(4)
listObject.remove(2)

dictionaryObject['Key1'] = 'Value1'
dictionaryObject['Key2'] = 'Value2'
dictionaryObject['Key3'] = 'Value3'
dictionaryObject.pop("Key1") #Remove an element from a dictionary

print(listObject)
print(dictionaryObject)
```

# Immutable

არამუტაბელური (Immutable) ობიექტები პითონში არის ისეთი ობიექტები, რომლების დარედაქტირება
შეუძლებელია იმის შემდეგ როდესაც მას ვქმნით. მაგალითად:

