# Edgistify

The website has been developed using the **MERN** stack. This repostiory contains all the files that have been used for the entire stack development. Follow the steps below to locally host the website on your system.

### Step 1: Add a default.json file in config folder with the folowing

```
"mongoURI": "<your_mongoDB_Atlas_uri_with_credentials>",
  "jwtSecret": "secret",
  "githubToken": ""
```

### Step 2:Install server dependencies

```
npm install
```

### Step 3:Install client dependencies

```
cd client
npm install
```

### Step 4:Run both Express & React from root

```
npm run dev
```

### Step 5:Build for production

```
cd client
npm run build
```


