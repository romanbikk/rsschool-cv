# Raman Bikchantayeu

# Contact information

[roman.bikchentaev@gmail.com](mailto:roman.bikchentaev@gmail.com)

## about myself

## Skills and Technologies:

## code example

```
function duplicateCount(text){
  if(!text.length) {
    return 0;
  }

  let count = 0;
  const charArr = text.toLocaleLowerCase().split('');
  const duplicatesMap = new Map();

  charArr.forEach((charEl) => {
    duplicatesMap.set(charEl, duplicatesMap.has(charEl) ? duplicatesMap.get(charEl) + 1 : 1);
  });
  duplicatesMap.forEach((val, _key) => {
    if (val > 1) {
      count++
    };
  });

  return count
}

```

## Languages:

## Certificates:
