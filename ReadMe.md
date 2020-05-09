# Create-Algo

create-algo is a cli used to generate a boilerplate for solving coding challenges.

## Installation

**npm**

```bash
npm install @frootloops/create-algo
```

**yarn**

```bash
yarn add @frootloops/create-algo
```

## Usage

It's nice to keep all of the coding challenges you solve in one directory for easy reference. I recommend that users create a directory and repository. Give it any name you like.

Then install `create-algo` in the newly crated directory as a dependency.

When you want to create a new boilerplate inside of your directory to solve a challenge simply run the `create-algo` command from your desired location inside your directory. You will then be prompted to chose and Javascript or Typescript and whether or not to initialize git. Simply choose using the arrow keys and press enter.

If you want to use typescript you have two choices, you can either initially run `create-algo typescript --install` or you can just run `create-algo` and then run `npm install` after selecting through the prompts.

Your boilerplate consisting of a package.json and a src folder with an index file will be installed in the directory of your choosing.

The package.json is bare bones and just provides you with the ability to run `test-algo` in the terminal to test your solution. Enjoy and happy coding!

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change. I am open to suggestions and ideas for enhancing this package.

## License

[MIT](https://choosealicense.com/licenses/mit/)
