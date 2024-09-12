# www-new

This is a Hugo-based website. Follow the instructions below to run this website locally.

## Prerequisites

- [Hugo](https://gohugo.io/getting-started/installing/) (extended version recommended)

## Setup

1. Clone the repository:

   ```sh
   git clone https://github.com/llvm/www-new.git
   cd www-new
   ```

2. Initialize and update the submodules (theme):

   ```sh
   git submodule update --init --recursive
   ```

3. Install postcss-cli
   ```sh
   npm install postcss-cli
   ```

## Running the Website Locally

1. Start the Hugo server:

   ```sh
   hugo server
   ```

2. Open your browser and navigate to `http://localhost:1313` to view the website.

## Additional Commands

- To build the website for production:

  ```sh
  hugo
  ```
