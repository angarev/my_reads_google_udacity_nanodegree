# MyReads App

MyReads is React app for listing books that you are interested in. The project is part from Udacity's React Fundamentals course. Books are sorted into three categories: Currently Reading, Want to Read and Read. To change a book's category or remove a book from the list, click on the green button on the book cover. To add new books, click on the green button at the bottom of the page. This button will open a search page. Enter an author's name or subject.

## Getting Started


1. Clone the repo `git clone https://github.com/angarev/project-myreads-starter.git`
2. cd into the project root and install all project dependencies with `npm install`
3. start the development server with `npm start`

A new browser window should automatically open displaying the app on URL- [http://localhost:3000/](http://localhost:3000/) in your browser


### Prerequisites

The project uses Node.js.  If you do not have Node you have to install from here - [Node.js](https://nodejs.org/en/). 

If you are using Ubuntu Precise or Debian Wheezy

```
curl -sL https://deb.nodesource.com/setup_10.x | sudo -E bash -
sudo apt-get install -y nodejs
```

## Backend Server

To simplify your development process, Udacity provided a backend server. The provided file [`BooksAPI.js`](src/BooksAPI.js) contains the methods to perform necessary operations on the backend:

* [`getAll`](#getall)
* [`update`](#update)
* [`search`](#search)

## Contributing

This project was bootstrapped with [Create React App](https://github.com/facebookincubator/create-react-app). You can find more information on how to perform common tasks [here](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md).


## License

This project is licensed under the MIT License - see the [LICENSE.md](https://opensource.org/licenses/MIT) for details.

