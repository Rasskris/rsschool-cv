## Rassoshenko Kristina

### Contact details

  __city__: Moscow

  __tel:__ +7(985)-229-33-86

  __email:__ rassoshenko.kristina@yandex.ru
  
  __telegram:__ @rasskris
  
______________________________

### Summary


JavaScript Frontend Developer is seeking an opportunity to extend my web development skills and knowledge.
______________________________

### Skills


| `Language`     | `Framework`        | `Librarie/API` | `Platform`   |
|:-------------: |:------------------:|:--------------:|:------------:|
| JavaScript     | Express.js.        | React          | MacOS        |
| HTML           | Bootsrap           | Redux-toolkit  | Linux        |  
| CSS            |                    | Node.js API    |              |
| SQL            |                    |                |              |
_______________________________

### Example code

This is example code of my study project (CLI utility).
This utility compares two configuration files and displays the result of the comparison in the console.
[You can see the full version](https://github.com/Rasskris/Generator-of-differences)

```javascript
const genDiff = (filepath1, filepath2, format = 'stylish') => {
  const fileType1 = getType(filepath1);
  const fileType2 = getType(filepath2);

  const fileContent1 = getContent(filepath1);
  const fileContent2 = getContent(filepath2);

  const data1 = parse(fileType1, fileContent1);
  const data2 = parse(fileType2, fileContent2);

  const diff = buildDiff(data1, data2);
  return render(diff, format);
};

```
_________________________

### Education

Course [Frontend Developer](https://ru.hexlet.io/programs/frontend), 2020-2021, __Hexlet__.

Elementary school teacher, 2016-2018, __Moscow Pedagogical State University__

Engineer of energy and resource-saving processes in chemical technology, petrochemistry and biotechnology, 2012-2016, __Peoples' Friendship University of Russia.__
