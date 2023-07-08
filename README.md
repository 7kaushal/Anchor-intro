# Introduction to Anchor Development

## What is Anchor ?
<p>Anchor is a powerful open-source framework that provides a simple and efficient way to build and deploy web applications. It offers developers a robust set of tools and features, allowing them to focus on creating high-quality applications without getting overwhelmed by complex infrastructure. It makes writing Solana programs easier, faster, and more secure. It's the "go to" framework for Solana development for very good reason.

With Anchor, you can quickly set up your application's backend, handle routing, manage databases, and implement authentication and authorization mechanisms. It follows a modular and scalable approach, making it easy to add new functionality and integrate with external services.</p>

## Installing Anchor

**For installing Anchor you will require:**

* [Rust](https://www.rust-lang.org/tools/install)
* [Solana](https://docs.solana.com/cli/install-solana-cli-tools)
 
  _Run `solana-keygen new` to create a keypair at the default location. Anchor uses this keypair to run your program tests._
* [Yarn](https://classic.yarnpkg.com/lang/en/docs/install/#windows-stable)

Install AVM using Cargo 

`cargo install --git https://github.com/coral-xyz/anchor avm --locked --force`

Install the latest version of the CLI using AVM

`avm install latest` 

`avm use latest`

For verifying:

`anchor --version`

## Running the Code
Run `anchor test`, you should see the following output: 

![success message](https://drive.google.com/uc?export=view&id=1oM_-d9aoKHJ1FVRUUgWa9fQ1KLzkaHCn)

Running anchor test automatically spins up a local test validator, deploys your program, and runs your mocha tests against it.
