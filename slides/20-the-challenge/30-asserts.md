### What about these tests?

```js
xit('should set default thresholds as expected', () => {
    expect(sut.thresholds).deep.eq(defaultThresholds);
});
```
    
```js
it('should have saved file', () => {
    sut.save('a file');
    // expect(TempFolder.writeFile).to.have.been.called;
});
```