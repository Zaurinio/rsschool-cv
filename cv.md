# Zaur Khutinaev

## Contacts

- Location: Moscow, Russia
- E-mail: zaurinio@inbox.ru
- GitHub: Zaurinio

## About Me

I'm 32 years old and I'm working as a junior frontend developer in fintech sphere.
In the course from RS School, I want to structure my knowledges and delve deeper into the intricacies of the Javascript language.

## My Skills

- HTML
- CSS (SASS)
- JavaScript
- Git
- Figma

## Code Examples

**Task Description:** The main idea is to count all the occurring characters in a string. If you have a string like aba, then the result should be {'a': 2, 'b': 1}.
What if the string is empty? Then the result should be empty object literal, {}.

```
function count (string) {
  const arr = string.split('');
  const result = {};
  arr.forEach((item) => {
    if (Object.keys(result).includes(item)) {
      result[item] += 1;
    } else {
      result[item] = 1;
    }
  })
   return result;
}
```

## Education

- **University:** HSE University, Logistics and SCM
- **Courses:**
  ++ HTML Academy, HTML and CSS. Professional website layout
  ++ HTML Academy, JavaScript. Professional web interface development
  ++ HTML Academy, React. Developing complex client applications

## Languages

- Russian - native
- English - intermediate
