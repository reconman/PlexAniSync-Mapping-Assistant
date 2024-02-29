<div align="center">

<a href="https://github.com/RickDB/PlexAniSync/">
    <img src="https://raw.githubusercontent.com/RickDB/PlexAniSync/master/logo.png" alt="PlexAniSync logo" title="PlexAniSync logo" width="80"/>
</a>

# [PlexAniSync](https://github.com/RickDB/PlexAniSync/) Mapping Assistant
TheMovieDB/TheTVDB Mapping Assistant for [PlexAniSync](https://github.com/RickDB/PlexAniSync/), specifically, for contribution to the [custom mappings](https://github.com/RickDB/PlexAniSync-Custom-Mappings) project.


<img src="https://github.com/Soitora/PlexAniSync-Mapping-Assistant/assets/10836780/8cf5acc2-fb19-483e-883e-53ceadfc7e94" alt="Assistant - Metadata selection" title="Assistant - Metadata selection" width="500"/>
<img src="https://github.com/Soitora/PlexAniSync-Mapping-Assistant/assets/10836780/2f02f5a8-cb23-47d5-b846-c96bd6ba4a48" alt="Assistant - Results from Movie search" title="Assistant - Results from Movie search" width="500"/>

### Repositories

[![RickDB/PlexAniSync - GitHub](https://github-readme-stats.vercel.app/api/pin/?username=RickDB&repo=PlexAniSync&bg_color=161B22&text_color=c9d1d9&title_color=0877d2&icon_color=0877d2&border_radius=8&hide_border=true)](https://github.com/RickDB/PlexAniSync/)
[![RickDB/PlexAniSync-Custom-Mappings - GitHub](https://github-readme-stats.vercel.app/api/pin/?username=RickDB&repo=PlexAniSync-Custom-Mappings&bg_color=161B22&text_color=c9d1d9&title_color=0877d2&icon_color=0877d2&border_radius=8&hide_border=true)](https://github.com/RickDB/PlexAniSync-Custom-Mappings/)

## Guide

</div>
<div align="left">

### Step 1: Prerequisites
Make sure you have `Node.js` and `npm` installed on your machine.
If not, you can download and install them from [Node.js official website](https://nodejs.org/).

### Step 2: Clone the Repository
Clone the repository to your local machine using the following command:

```bash
git clone https://github.com/Soitora/PlexAniSync-Mapping-Assistant.git
```

### Step 3: Navigate to Project Directory
Change into the project directory:

```bash
cd PlexAniSync-Mapping-Assistant
```

### Step 4: Install Dependencies
Run the following command to install project dependencies:

```bash
npm install
```

### Step 5: Create .env file
Copy the provided `.env.example` file to a new file named `.env`:

```bash
cp .env.example .env
```

### Step 6: Edit .env File
Open the `.env` file in a text editor and fill in the environment variables with appropriate values.

</div>

> [!NOTE]
>- You do not need both `TMDB_APIKEY` and `TVDB_APIKEY` to run this, only one is required at minimum.
>- You do not need to tweak/add `DUMMY_QUERY` unless that doesn't work for you.
>- Both `PLEX_TOKEN` and `PLEX_API` is also optional, but highly recommended for `guid` in the output.

<div align="left">

### Step 7: Run the Assistant
You can now run the mapping assistant using the following command:

```bash
npm run assistant
```

### Step 8: Debugging (Optional)
If you need to debug and test towards API directly, you can use the following command:

```bash
npm run debug
```

### Step 9: Auto-scraping (Optional)
If you would prefer to input a large number of IDs, and have the program output a file for you, you can do it using this script.

Make sure that you fill `batch\input.txt` with a newline-seperated list of IDs.

```bash
npm run auto
```

### Step 10: Testing (Optional)
To run tests to make sure the API is spitting out the correct information, use the following command:

```bash
npm test
```

</div>
<div align="center">

## Scripts

<div align="left">

- `assistant`: Runs the assistant script
- `debug`: Runs the debug script to see raw outputs of APIs

</div>

## Issues
If you have any issues, please open a new issue in the [Issues](https://github.com/Soitora/PlexAniSync-Mapping-Assistant/issues) section of this repository.

### Credits

Thank you to all the people who have contributed!

<a href="https://github.com/Soitora/PlexAniSync-Mapping-Assistant/graphs/contributors">
    <img src="https://contrib.rocks/image?repo=Soitora/PlexAniSync-Mapping-Assistant" alt="PlexAniSync Mapping Assistant contributors" title="PlexAniSync Mapping Assistant contributors"/>
</a>

## License
<pre>
Copyright © 2023 Soitora

This Source Code Form is subject to the terms of the Mozilla Public
License, v. 2.0. If a copy of the MPL was not distributed with this
file, You can obtain one at http://mozilla.org/MPL/2.0/.
</pre>

</div>
