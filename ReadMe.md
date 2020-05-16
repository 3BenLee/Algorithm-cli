# Create-Algo

create-algo is a cli used to generate a boilerplate for solving coding challenges.

You can install this globally and use it to create a quick boilerplate but I think it's nice to keep all of the coding challenges you solve in one directory for easy reference. I recommend that users create a parent directory and repository. Give it any name you like.

Then install `create-algo` in the newly created parent directory as a dependency. I usually create a child directory inside the parent with the name of the challenge I am solving and run `create-algo` in this newly created child directory to generate a boilerplate.

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

When you want to create a new boilerplate inside of your parent directory to solve a new challenge simply run the `create-algo` command from your desired location inside your parent directory. You will then be prompted to chose Javascript or Typescript and whether or not to initialize git. If you are creating this directory as a stand alone directory then you may want to chose yes to initialize. If this is a subdirectory then I always choose no because the parent directory is the initialized repo and that's where we are now housing this new child directory.

If you want to use Typescript you have two choices, you can either initially run `create-algo typescript --install` or you can just run `create-algo` and then run `npm install` after selecting through the prompts. Either way the Typescript dependencies will be installed.

Your boilerplate consisting of a `package.json`, a `src` folder with an index file for your code, and a `.gitignore` will be installed in the directory of your choosing.

The `package.json` is bare bones and just provides you with the ability to run `test-algo` in the terminal to test your solution.

The `.gitignore` initially contains the `node_modules`, which we don't need to push to our repo. You can add any other files here if you need to later on.

Enjoy and happy coding!

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change. I am open to suggestions and ideas for enhancing this package.

## License

[MIT](https://choosealicense.com/licenses/mit/)
