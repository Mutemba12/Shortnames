All modes that use C style folding (C, JavaScript, CSS, etc...) support non-standard code folding using special comment notations:

### Region Folding

 - Supported using lineComment or blockComment (blockComment is needed primarily for CSS mode)
 - lineComment example:

```javascript
//#region [optional description]
     [code that will be folded here]
//#endregion 
```

 - blockComment example:
```javascript
/*#region [optional description]*/
     [code that will be folded here]
/*#endregion*/
```

### Triple Star (Asterisk) Folding

 - Single line blockComments that start with 3 stars will render a fold widget that folds the comment and the code below it
```javascript
/*** [optional description] ***/
     [code that will be folded here]
```
