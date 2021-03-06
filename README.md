# Infoportal

[![Build status](https://dev.azure.com/brreg/altinn-infoportal/_apis/build/status/altinn-infoportal-CI?label=altinn/infoportal)](https://dev.azure.com/brreg/altinn-infoportal/_build/latest?definitionId=217)

## Running altinn-infoportal locally

1. Clone the repo (assumes you've installed [Git](https://git-scm.com/downloads)):
   ```shell
   cd C:/repos
   git clone https://github.com/Altinn/altinn-infoportal
   ```
2. [Download Hugo](https://github.com/gohugoio/hugo/releases) (v0.80.0 or newer), and copy the executable for your OS into the new `altinn-infoportal` folder.   
3. Navigate to folder and run Hugo
   ```shell
   cd altinn-infoportal
   ./hugo serve --navigateToChanged
   ```

Which will result in output similar to:
```cmd
Start building sites …

                   | NB  | EN  | NN   
-------------------+-----+-----+------
  Pages            |  27 |  19 |  19  
  Paginator pages  |   0 |   0 |   0  
  Non-page files   |   4 |   4 |   4  
  Static files     | 503 | 503 | 503  
  Processed images |   0 |   0 |   0  
  Aliases          |  12 |  10 |  10  
  Sitemaps         |   2 |   1 |   1  
  Cleaned          |   0 |   0 |   0  

Built in 10707 ms
Watching for changes in C:\repos\altinn-infoportal\{content,i18n,layouts,static,themes}
Watching for config changes in C:\repos\altinn-infoportal\config.toml
Environment: "development"
Serving pages from memory
Running in Fast Render Mode. For full rebuilds on change: hugo server --disableFastRender
Web Server is available at http://localhost:1313/ (bind address 127.0.0.1)
Press Ctrl+C to stop
```

The solution is now running locally at http://localhost:1313
