

# MultiFrameworkMfeNx

This project was generated using [Nx](https://nx.dev).

Run `npx create-nx-workspace`

cd multi-framework-mfe-nx

Run `npm install --save-dev @nrwl/angular`

Run `npx nx g @nrwl/angular:app angular-shell --mfe --mfeType=host --routing=true`

Run `npx nx g @nrwl/angular:app angular-mfe --mfe --mfeType=remote --port=4201 --host=angular-shell --routing=true`

Run `npm install --save-dev @nrwl/react`

Run `npx nx g @nrwl/react:app react-shell --mfe --mfeType=host --port=5200 --routing=true`

Run `npx nx g @nrwl/react:app react-mfe --mfe --mfeType=remote --port=5201 --host=angular-shell --routing=true`

Run `npx nx g @nrwl/web:webpack5`

Run `nx run angular-shell:serve-mfe`

Run `nx g component home --project=angular-shell`

Run `nx g component not-found --project=angular-shell`