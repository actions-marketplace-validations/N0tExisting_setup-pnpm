# Setup Pnpm

Automatically:
- Clone your repository
- Setup PNPM with your specified version
- _Setup Node with your specified version_
- Install your dependencies using pnpm

## Usage
```yml
    steps:
      - name: Setup
        uses: N0tExisting/setup-pnpm@v1
        with:
          node-version: ${{ matrix.node-version }}
          pnpm-version: ${{ env.pnpm-version }}
```
