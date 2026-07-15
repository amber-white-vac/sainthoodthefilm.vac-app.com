# Sainthood Coming Soon Page

Static GitHub Pages homepage for the Sainthood subdomain.

## Publish on GitHub Pages

1. Create a new GitHub repository.
2. Upload these files to the repository root.
3. In GitHub, go to Settings -> Pages.
4. Set Source to "Deploy from a branch".
5. Choose `main` and `/root`.
6. For the subdomain, add your custom domain in Pages settings.

For DNS, create a `CNAME` record for the subdomain that points to:

```txt
your-github-username.github.io
```

This site includes a `CNAME` file for:

```txt
sainthoodtheseries.vac-app.com
```
