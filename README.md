usereducer(counterReducer, initialState)就是当逻辑较为复杂，setState要触发多次时，可以用它。 把复杂的逻辑写在counterReducer里。而页面只需要输入if判断的值就行。一般是type。conterReducer(state, action)  action.type
