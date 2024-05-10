dfx start --clean

{
    "canisters": {
      "vanilla-icp": {
        "frontend": {
          "entrypoint": "src/index.html"
        },
        "source": ["src"],
        "type": "assets"
      }
    },
    "dfx": "0.17.0",
    "version": 1
  }

  dfx deploy
