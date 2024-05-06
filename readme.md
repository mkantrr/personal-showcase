# mattkanter.com

This is one of two repositories created for my portfolio website <a href="https://mattkanter.com/"><samp>mattkanter.com</samp></a>. Thanks for taking the time to check this out. If you have any questions of comments, feel free to shoot me an email at <samp><a href="mailto:matthew@mattkanter.com">matt@matutu.dev</a></samp>.

<br>

To setup a dev environment:

```bash
# Clone the repository

cd dev_website

# Install dependencies 
npm i

# Run the local dev server
npm run dev
```

Setup OS inner site dev environment:

```bash
cd kanter_os

#Install dependencies
npm i

#Run the local dev server
npm start
```

To serve a production build:

```bash
# Install dependencies if not already done - 'npm i'

cd dev_website

# Build for production
npm run build

# Serve the build using express
npm start
```

To server the inner OS site production build:

```bash
# Install dependencies if not already done - 'npm i'

cd kanter_os

# Build for production
npm run build

# Serve the build
serve -s build
```

