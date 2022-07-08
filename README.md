# code-samples
Some samples of code for testing / educational purposes

### converts fraction from binary system into decimal one
```javascript
[...'000110011001100110011001100110011001100110011001100'].reduce((acc, ch, i) => acc + Number(ch) * 2 ** (-i - 1), 0)
```
or a bit shorter :)
```javascript
[...'000110011001100110011001100110011001100110011001100'].reduce((acc, ch, i) => +ch * 2 ** (-i - 1) + acc, 0)
```
