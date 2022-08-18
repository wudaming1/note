# 柯里化
curry化来源与数学家 Haskell Curry的名字 （编程语言 Haskell也是以他的名字命名）。柯里化通常也称部分求值，其含义是给函数分步传递参数，每次传递参数后部分应用参数，并返回一个更具体的函数接受剩下的参数，这中间可嵌套多层这样的接受部分参数函数，直至返回最后结果。因此柯里化的过程是逐步传参，逐步缩小函数的适用范围，逐步求解的过程。
