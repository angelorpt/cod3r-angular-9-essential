# Angular 9 Essential

## To Run:


## Steps In Development:

### 1. Back-end
```bash
cd backend
npm init -y
npm i json-server
```
### 2. Front-end

#### 2.1. Inicial

```bash
cd ..
sudo npm i -g @angular/cli
ng new frontend
install router? y
witch (css, scss, sass)? scss
cd frontend
npm start
```

#### 2.2. material

```bash
ng add @angular/material
```

#### 2.3 component

```bash
ng generate component components/template/header
#or
ng g c components/template/header
```

#### 2.4 normalize.css

```bash
npm install --save normalize.css
```

```scss
// frontend/src/styles.scss
@import "~normalize.css";

// ...

a {
  all: unset;
  cursor: pointer;
}
```
