# [Open Résumé Example](https://open-resume.orleans.io) [![release](https://github.com/dudeofawesome/open-resume-example/actions/workflows/release.yaml/badge.svg)](https://github.com/dudeofawesome/open-resume-example/actions/workflows/release.yaml)

## Building your own résumé

1.  [Create your own repository from this template repo](https://github.com/dudeofawesome/open-resume-example/generate).

1.  Ensure that GitHub Pages are enabled in your new resume

    1.  Ensure that the Pages source is set to "GitHub Actions"

        <img width="301" alt="image" src="https://user-images.githubusercontent.com/1683595/228087870-02fbb377-b538-482f-b5a3-ff7636584b34.png">

    1.  Set a custom domain name for GitHub Pages. The default build configuration does not support GitHub Pages without a custom domain.

1.  Clone your repo.
1.  Install dependencies.
    ```bash
    $ npm install
    ```
1.  Start the dev server.
    ```bash
    $ npm run dev
    ```
1.  Update [`/src/data.ts`](/src/data.ts) & [`/package.json`](/package.json) with your own info.
1.  Replace [`/public/icon.svg`](/public/icon.svg) with your own logo.
1.  Commit & push your changes.
1.  GitHub Actions will now build and deploy your resume!
