# MERN app with Auth, MUI

## Frontend

- MERN stack
- FORMIK + yup - form validation
- Redux Toolkit - state management
- Redux with Persistent - store in localstorage
- React Dropzone
- MUI

### Dependencies

`npm install react-redux @reduxjs/toolkit redux-persist react-dropzone dotenv formik yup react-router-dom@6 @mui/material @emotion/react @emotion/styled @mui/icons-material state`

### logobox

```javascript
<Box
  width='100%'
  backgroundColor={theme.palette.background.alt}
  p='1rem 6%'
  textAlign='center'
  display='flex'
  justifyContent='center'
  alignItems='center'
>
  <img
    src='./assets/logo.png'
    alt='logo'
    style={{ width: '45px', height: '45px' }}
  />
  <Typography fontWeight='bold' fontSize='32px' color='primary' ml='5px'>
    Socio
  </Typography>
</Box>
```

### Color

```javascript
primary: {
    50: '#ede7f6',
    100: '#d1c4e9',
    200: '#b39ddb',
    300: '#9575cd',
    400: '#7e57c2',
    500: '#673ab7',
    600: '#5e35b1',
    700: '#512da8',
    800: '#4527a0',
    900: '#311b92',
  },
```

## Backend

- nodejs
- expressjs
- mongoose
- jwt - authentication
- Multer - file upload

### Dependencies

`npm install nodemon express body-parser bcrypt cors dotenv gridfs-stream multer multer-gridfs-storage helmet morgan jsonwebtoken mongoose`

- add package.json
  `"type": "module",`

### MongoDB
