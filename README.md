# LycoFund

The smartest way to invest in digital assets

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

#curl 
``` 
sudo apt-get install curl 
```

#nix package manager 
``` 
curl https://nixos.org/nix/install | sh 
```

#dapp
``` 
curl https://nixos.org/nix/install | sh
nix-channel --add https://nix.dapphub.com/pkgs/dapphub
nix-channel --update
nix-env -iA dapphub.{dapp,seth,hevm,evmdis}
```

#rust 
```
curl https://sh.rustup.rs -sSf | sh
```

#parity
```
git clone https://github.com/paritytech/parity
cd parity
cargo build --release
```

#Melon Protocol 
```
git clone https://github.com/melonproject/protocol.git
cd protocol
npm install
npm run compile
```

### Installing



## Running the tests



### Break down into end to end tests



### And coding style tests



## Deployment



## Built With



## Contributing



## Versioning



## Authors



## License



## Acknowledgments



