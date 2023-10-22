yarn nx workspace-schematic generate-library
yarn nx affected:build --prod --parallel
yarn nx affected:build --prod --parallel --only-failed
yarn nx generate @nrwl/angular

#commands #nx 