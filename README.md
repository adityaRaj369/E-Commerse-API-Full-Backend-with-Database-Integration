<p align="center">
  <img src="https://cdn-icons-png.flaticon.com/512/6295/6295417.png" width="100" />
</p>
<p align="center">
    <h1 align="center">E-COMMERSE-API-FULL-BACKEND-WITH-DATABASE-INTEGRATION</h1>
</p>
<p align="center">
    <em>HTTP error 401 for prompt `slogan`</em>
</p>
<p align="center">
	<img src="https://img.shields.io/github/license/adityaRaj369/E-Commerse-API-Full-Backend-with-Database-Integration?style=flat&color=0080ff" alt="license">
	<img src="https://img.shields.io/github/last-commit/adityaRaj369/E-Commerse-API-Full-Backend-with-Database-Integration?style=flat&logo=git&logoColor=white&color=0080ff" alt="last-commit">
	<img src="https://img.shields.io/github/languages/top/adityaRaj369/E-Commerse-API-Full-Backend-with-Database-Integration?style=flat&color=0080ff" alt="repo-top-language">
	<img src="https://img.shields.io/github/languages/count/adityaRaj369/E-Commerse-API-Full-Backend-with-Database-Integration?style=flat&color=0080ff" alt="repo-language-count">
<p>
<p align="center">
		<em>Developed with the software and tools below.</em>
</p>
<p align="center">
	<img src="https://img.shields.io/badge/JavaScript-F7DF1E.svg?style=flat&logo=JavaScript&logoColor=black" alt="JavaScript">
	<img src="https://img.shields.io/badge/MongoDB-47A248.svg?style=flat&logo=MongoDB&logoColor=white" alt="MongoDB">
	<img src="https://img.shields.io/badge/Express-000000.svg?style=flat&logo=Express&logoColor=white" alt="Express">
	<img src="https://img.shields.io/badge/JSON-000000.svg?style=flat&logo=JSON&logoColor=white" alt="JSON">
</p>
<hr>

##  Quick Links

> - [ Overview](#-overview)
> - [ Features](#-features)
> - [ Repository Structure](#-repository-structure)
> - [ Modules](#-modules)
> - [ Getting Started](#-getting-started)
>   - [ Installation](#-installation)
>   - [ Running E-Commerse-API-Full-Backend-with-Database-Integration](#-running-E-Commerse-API-Full-Backend-with-Database-Integration)
>   - [ Tests](#-tests)
> - [ Project Roadmap](#-project-roadmap)
> - [ Contributing](#-contributing)
> - [ License](#-license)
> - [ Acknowledgments](#-acknowledgments)

---

##  Overview

This repo consists of E-Commerse API With full Backend Implementation with database connectivity

---

##  Features
-User(Login,SignUp)
-Products(Add Product,Get Product,Filter Product,Delete Product)
-Cart(Add,get,Delete)
-Order(Place Order,MongoDB Database transaction Implemented)
-JWT Authentication
-Database


---

##  Repository Structure

```sh
└── E-Commerse-API-Full-Backend-with-Database-Integration/
    ├── APILIst.txt
    ├── LICENSE
    ├── log.txt
    ├── package-lock.json
    ├── package.json
    ├── server.js
    ├── src
    │   ├── config
    │   │   └── mongodb.js
    │   ├── error-handler
    │   │   └── applicationError.js
    │   ├── features
    │   │   ├── cartItems
    │   │   │   ├── cartItems.controller.js
    │   │   │   ├── cartItems.model.js
    │   │   │   ├── cartItems.repository.js
    │   │   │   └── cartItems.routes.js
    │   │   ├── order
    │   │   │   ├── info.txt
    │   │   │   ├── order.controller.js
    │   │   │   ├── order.model.js
    │   │   │   ├── order.repository.js
    │   │   │   └── order.routes.js
    │   │   ├── product
    │   │   │   ├── product.controller.js
    │   │   │   ├── product.model.js
    │   │   │   ├── product.repository.js
    │   │   │   └── product.routes.js
    │   │   └── user
    │   │       ├── user.controller.js
    │   │       ├── user.model.js
    │   │       ├── user.repository.js
    │   │       └── user.routes.js
    │   └── middlewares
    │       ├── basicAuth.middleware.js
    │       ├── fileupload.middleware.js
    │       ├── jwt.middleware.js
    │       └── logger.middleware.js
    ├── steps.txt
    ├── swagger.json
    └── uploads
        ├── 2023-05-02T07_14_23.097ZUntitled.png
        ├── 2023-07-24T08_31_00.909Ziphone.png
        ├── 2023-07-24T08_32_19.276Ziphone.png
        └── 2023-07-24T08_33_11.427Ziphone.png
```

---

##  Modules

<details closed><summary>.</summary>

| File                                                                                                                                     | Summary                                       |
| ---                                                                                                                                      | ---                                           |
| [log.txt](https://github.com/adityaRaj369/E-Commerse-API-Full-Backend-with-Database-Integration/blob/master/log.txt)                     | HTTP error 401 for prompt `log.txt`           |
| [server.js](https://github.com/adityaRaj369/E-Commerse-API-Full-Backend-with-Database-Integration/blob/master/server.js)                 | HTTP error 401 for prompt `server.js`         |
| [package.json](https://github.com/adityaRaj369/E-Commerse-API-Full-Backend-with-Database-Integration/blob/master/package.json)           | HTTP error 401 for prompt `package.json`      |
| [steps.txt](https://github.com/adityaRaj369/E-Commerse-API-Full-Backend-with-Database-Integration/blob/master/steps.txt)                 | HTTP error 401 for prompt `steps.txt`         |
| [swagger.json](https://github.com/adityaRaj369/E-Commerse-API-Full-Backend-with-Database-Integration/blob/master/swagger.json)           | HTTP error 401 for prompt `swagger.json`      |
| [package-lock.json](https://github.com/adityaRaj369/E-Commerse-API-Full-Backend-with-Database-Integration/blob/master/package-lock.json) | HTTP error 401 for prompt `package-lock.json` |
| [APILIst.txt](https://github.com/adityaRaj369/E-Commerse-API-Full-Backend-with-Database-Integration/blob/master/APILIst.txt)             | HTTP error 401 for prompt `APILIst.txt`       |

</details>

<details closed><summary>src.error-handler</summary>

| File                                                                                                                                                           | Summary                                                           |
| ---                                                                                                                                                            | ---                                                               |
| [applicationError.js](https://github.com/adityaRaj369/E-Commerse-API-Full-Backend-with-Database-Integration/blob/master/src/error-handler/applicationError.js) | HTTP error 401 for prompt `src/error-handler/applicationError.js` |

</details>

<details closed><summary>src.config</summary>

| File                                                                                                                                  | Summary                                           |
| ---                                                                                                                                   | ---                                               |
| [mongodb.js](https://github.com/adityaRaj369/E-Commerse-API-Full-Backend-with-Database-Integration/blob/master/src/config/mongodb.js) | HTTP error 401 for prompt `src/config/mongodb.js` |

</details>

<details closed><summary>src.features.order</summary>

| File                                                                                                                                                            | Summary                                                            |
| ---                                                                                                                                                             | ---                                                                |
| [order.controller.js](https://github.com/adityaRaj369/E-Commerse-API-Full-Backend-with-Database-Integration/blob/master/src/features/order/order.controller.js) |Controller Class for Order `src/features/order/order.controller.js` |
| [order.repository.js](https://github.com/adityaRaj369/E-Commerse-API-Full-Backend-with-Database-Integration/blob/master/src/features/order/order.repository.js) | Repository for Order `src/features/order/order.repository.js` |
| [info.txt](https://github.com/adityaRaj369/E-Commerse-API-Full-Backend-with-Database-Integration/blob/master/src/features/order/info.txt)                       | `src/features/order/info.txt`            |
| [order.model.js](https://github.com/adityaRaj369/E-Commerse-API-Full-Backend-with-Database-Integration/blob/master/src/features/order/order.model.js)           | Model Class for Order `src/features/order/order.model.js`      |
| [order.routes.js](https://github.com/adityaRaj369/E-Commerse-API-Full-Backend-with-Database-Integration/blob/master/src/features/order/order.routes.js)         | Route for the Order `src/features/order/order.routes.js`     |

</details>

<details closed><summary>src.features.product</summary>

| File                                                                                                                                                                  | Summary                                                                |
| ---                                                                                                                                                                   | ---                                                                    |
| [product.controller.js](https://github.com/adityaRaj369/E-Commerse-API-Full-Backend-with-Database-Integration/blob/master/src/features/product/product.controller.js) | Controller Class for Product `src/features/product/product.controller.js` |
| [product.repository.js](https://github.com/adityaRaj369/E-Commerse-API-Full-Backend-with-Database-Integration/blob/master/src/features/product/product.repository.js) | Repository for Product `src/features/product/product.repository.js` |
| [product.routes.js](https://github.com/adityaRaj369/E-Commerse-API-Full-Backend-with-Database-Integration/blob/master/src/features/product/product.routes.js)         | Route for the Product `src/features/product/product.routes.js`     |
| [product.model.js](https://github.com/adityaRaj369/E-Commerse-API-Full-Backend-with-Database-Integration/blob/master/src/features/product/product.model.js)           | Model Class for Product `src/features/product/product.model.js`      |

</details>

<details closed><summary>src.features.cartItems</summary>

| File                                                                                                                                                                        | Summary                                                                    |
| ---                                                                                                                                                                         | ---                                                                        |
| [cartItems.model.js](https://github.com/adityaRaj369/E-Commerse-API-Full-Backend-with-Database-Integration/blob/master/src/features/cartItems/cartItems.model.js)           | Model Class for cart `src/features/cartItems/cartItems.model.js`      |
| [cartItems.repository.js](https://github.com/adityaRaj369/E-Commerse-API-Full-Backend-with-Database-Integration/blob/master/src/features/cartItems/cartItems.repository.js) | Repository for cart `src/features/cartItems/cartItems.repository.js` |
| [cartItems.controller.js](https://github.com/adityaRaj369/E-Commerse-API-Full-Backend-with-Database-Integration/blob/master/src/features/cartItems/cartItems.controller.js) | Controller Class for cart `src/features/cartItems/cartItems.controller.js` |
| [cartItems.routes.js](https://github.com/adityaRaj369/E-Commerse-API-Full-Backend-with-Database-Integration/blob/master/src/features/cartItems/cartItems.routes.js)         | Route for the cart `src/features/cartItems/cartItems.routes.js`     |

</details>

<details closed><summary>src.features.user</summary>

| File                                                                                                                                                         | Summary                                                          |
| ---                                                                                                                                                          | ---                                                              |
| [user.model.js](https://github.com/adityaRaj369/E-Commerse-API-Full-Backend-with-Database-Integration/blob/master/src/features/user/user.model.js)           |  Model Class for user `src/features/user/user.model.js`      |
| [user.controller.js](https://github.com/adityaRaj369/E-Commerse-API-Full-Backend-with-Database-Integration/blob/master/src/features/user/user.controller.js) | Controller Class for user `src/features/user/user.controller.js` |
| [user.repository.js](https://github.com/adityaRaj369/E-Commerse-API-Full-Backend-with-Database-Integration/blob/master/src/features/user/user.repository.js) | Repository for user `src/features/user/user.repository.js` |
| [user.routes.js](https://github.com/adityaRaj369/E-Commerse-API-Full-Backend-with-Database-Integration/blob/master/src/features/user/user.routes.js)         | Route for the user `src/features/user/user.routes.js`     |

</details>

<details closed><summary>src.middlewares</summary>

| File                                                                                                                                                                   | Summary                                                              |
| ---                                                                                                                                                                    | ---                                                                  |
| [basicAuth.middleware.js](https://github.com/adityaRaj369/E-Commerse-API-Full-Backend-with-Database-Integration/blob/master/src/middlewares/basicAuth.middleware.js)   | Authentication Middleware `src/middlewares/basicAuth.middleware.js`  |
| [logger.middleware.js](https://github.com/adityaRaj369/E-Commerse-API-Full-Backend-with-Database-Integration/blob/master/src/middlewares/logger.middleware.js)         | Logger Middleware `src/middlewares/logger.middleware.js`     |
| [fileupload.middleware.js](https://github.com/adityaRaj369/E-Commerse-API-Full-Backend-with-Database-Integration/blob/master/src/middlewares/fileupload.middleware.js) |File upload Middleware `src/middlewares/fileupload.middleware.js` |
| [jwt.middleware.js](https://github.com/adityaRaj369/E-Commerse-API-Full-Backend-with-Database-Integration/blob/master/src/middlewares/jwt.middleware.js)               | JWT Authentication Middleware `src/middlewares/jwt.middleware.js`        |

</details>

---

##  Getting Started

***Requirements***

Ensure you have the dependencies installed on your system: 



###  Installation

1. Clone the E-Commerse-API-Full-Backend-with-Database-Integration repository:

```sh
git clone https://github.com/adityaRaj369/E-Commerse-API-Full-Backend-with-Database-Integration
```

2. Change to the project directory:

```sh
cd E-Commerse-API-Full-Backend-with-Database-Integration
```

3. Install the dependencies:

```sh
npm install
```

###  Running E-Commerse-API-Full-Backend-with-Database-Integration

Use the following command to run E-Commerse-API-Full-Backend-with-Database-Integration:

```sh
node server.js
```



---


---

##  Contributing

Contributions are welcomed!


<details closed>
    <summary>Contributing Guidelines</summary>

1. **Fork the Repository**: Start by forking the project repository to your GitHub account.
2. **Clone Locally**: Clone the forked repository to your local machine using a Git client.
   ```sh
   git clone https://github.com/adityaRaj369/E-Commerse-API-Full-Backend-with-Database-Integration
   ```
3. **Create a New Branch**: Always work on a new branch, giving it a descriptive name.
   ```sh
   git checkout -b new-feature-x
   ```
4. **Make Your Changes**: Develop and test your changes locally.
5. **Commit Your Changes**: Commit with a clear message describing your updates.
   ```sh
   git commit -m 'Implemented new feature x.'
   ```
6. **Push to GitHub**: Push the changes to your forked repository.
   ```sh
   git push origin new-feature-x
   ```
7. **Submit a Pull Request**: Create a PR against the original project repository. Clearly describe the changes and their motivations.

Once your PR is reviewed and approved, it will be merged into the main branch.

</details>

---

##  License

This project is protected under the [MIT](https://choosealicense.com/licenses) License.

---
