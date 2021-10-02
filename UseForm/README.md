# useForm Hook

Ejemplo de uso: 
```
    const initialForm = {
        name: '',
        edad: 0,
        email: '',
    }
    const [ formValues, handleInputChange, reset ] = useForm(initialForm);

    const { name, email } = formValues;

    <input type="text" placeholder="tu nombre" autoComplete="off" name="name" value={ name } onChange={ handleInputChange } />

    <input type="email" placeholder="tucorreo@gmail.com" autoComplete="off" name="email" value={ email } onChange={ handleInputChange } />

```