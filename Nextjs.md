# Gradual Typing
  Annotation 註記所有型別
  Inference 推論所有型別
  Assertion 斷言

```
  此處並非箭頭符號，而是一種註記方式
  const isPositive: (input: number) => boolean = input => input > 0;
  const isPositive = function(input: number): boolean {
    input > 0;
  }
  const isPositive = function(input: number): boolean => input > 0;
```

#
