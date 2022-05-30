# How to host Swagger API documentation with GitHub Pages

1. Copy the `docs` folder to your project
 
2. Replace the YAML specification file with yours to the root of your repository.

3. Edit `index.html` and change the `schema_yaml` property to reference your local YAML file.

    ```html
        <script src="dist/swagger-initializer.js" charset="UTF-8" id="init" schema_yaml="industry_metrics.yaml"> </script>
        ...
    ```
    
4. Go to the settings for your repository at `https://github.com/{github-username}/{repository-name}/settings` and enable GitHub Pages.

    ![Headers](screenshots/swagger-github-pages.png?raw=true)
    
5. Browse to the Swagger documentation using the github-pages link in the right panel

   ![Headers](screenshots/pages_link.png?raw=true)
