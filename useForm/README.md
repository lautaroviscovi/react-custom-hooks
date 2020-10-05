# useForm Hook

Example:

```
    const initialForm = {
        name: '',
        age: 33,
        email: ''
        ... Data
    };
    
    const [ Formvalues, handleInputChange, reset ] = useForm( initialForm );
```