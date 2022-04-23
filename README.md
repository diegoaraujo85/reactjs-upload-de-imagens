<p align="center">
  <a href="" rel="noopener">
 <img width=200px height=200px src="./public/logo.svg" alt="Upfi"></a>
</p>

<h3 align="center">upfi - upload de imagens</h3>

<div align="center">

[![Status](https://img.shields.io/badge/status-active-success.svg)]()
[![GitHub Issues](https://img.shields.io/github/issues/diegoaraujo85/reactjs-upload-de-imagens.svg)](https://github.com/diegoaraujo85/reactjs-upload-de-imagens/issues)
[![GitHub Pull Requests](https://img.shields.io/github/issues-pr/diegoaraujo85/reactjs-upload-de-imagens.svg)](https://github.com/diegoaraujo85/reactjs-upload-de-imagens/pulls)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](/LICENSE)

</div>

---

<p align="center"> Projeto de Upload de imagens utilizando <a href="https://nextjs.org">Next.Js</a>, <a href="https://fauna.com/">FaunaDB</a> e <a href="https://imgbb.com/">ImgBB</a>
    <br>
</p>

## 📝 Table of Contents

- [Installing](#installing)
- [Usage](#usage)
- [Built Using](#built_using)

### Before All
You will need to create an [account in ImgBB](https://imgbb.com/login)
And [create an apiKey](https://api.imgbb.com/)
Copy the key to `NEXT_PUBLIC_IMGBB_API_KEY=APIKEY_VALUE` in `.env.local` file

You need to create a [Fauna Account](https://fauna.com/) also.
Create a database and a collection named `images`.
Go to security ans create an apiKey named as you prefer, copy the value to `FAUNA_API_KEY`

## Installing <a name = "installing"></a>

```
git clone https://github.com/diegoaraujo85/reactjs-upload-de-imagens
```

```
cd reactjs-upload-de-imagens
```

```
yarn install
```

```
yarn dev
```

## 🔧 Running the tests <a name = "tests"></a>

```
yarn test
```
or to generate de coverage report
```
yarn coverage
```

## ⛏️ Built Using <a name = "built_using"></a>

- [Next.Js](https://nextjs.org) - Framework
- [FaunaDB](https://fauna.com/) - Database
- [ImgBB](https://imgbb.com/) - Image CDN
- [Chakra UI](https://chakra-ui.com)
- [Axios](https://axios-http.com/)
- [Multer](https://github.com/expressjs/multer)
- [React Hook Form](https://react-hook-form.com)
- [Yup](https://github.com/jquense/yup)
- [React JS](https://pt-br.reactjs.org)
