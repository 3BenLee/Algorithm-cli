# Create-Algo

create-algo is a cli used to generate a boilerplate for solving coding challenges.

You can install this globally and use it to create a quick boilerplate but I think it's nice to keep all of the coding challenges you solve in one directory for easy reference. I recommend that users create a parent directory and repository. Give it any name you like.

Then install `create-algo` in the newly created parent directory as a dependency.

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

When you want to create a new boilerplate to solve a new challenge simply run the `create-algo` command from your desired location inside your directory. You will then be prompted to chose Javascript or Typescript. Then you will be prompted to name your new subdirectory. I usually give it the name of the challenge I am solving and maybe even the site it came from for reference.

Your boilerplate consisting of a `package.json`, an index file for your code, and a `.gitignore` will be installed.

The `package.json` is bare bones and just provides you with the ability to run `test-algo` in the terminal to test your solution.

The `.gitignore` initially contains the `node_modules`, which we don't need to push to our repo. You can add any other files here if you need to later on.

Enjoy and happy coding!

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change. I am open to suggestions and ideas for enhancing this package.

## License

[MIT](https://choosealicense.com/licenses/mit/)
