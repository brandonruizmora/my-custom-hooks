# useCounter Hook

Ejemplo de uso: 
```
    const { counter, increment, decrement, reset } = useCounter(10);
```

useCounter(); // recibe un valor por defecto de 0

counter; // (int) valor del contador

increment(); // (Function) incrementa en 1
increment(5); // (Function) incrementa en 5

decrement(); // (Function) resta en 1
decrement(5); // (Function) resta en 5

reset(); // (Function) resetea al valor con el que fue inicializado
