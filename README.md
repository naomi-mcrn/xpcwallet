# xpcwallet.rb: A stand-alone XPChain client

説明はフォーク元を参照のこと。

## Features

* Stand-alone XPChain client 
  * Generate address, export key, show balances for addresses, send coins from addresses ...
* Written in pure Ruby
  * No additional dependencies
* Implements Simplified Payment Verification (SPV)
* Comments to help you understand how XPChain client is implemented
* Testnet supported (use in main network is not recommended)

## Usage

    Usage: ruby xpcwallet.rb <command> [<args>]
    commands:
        generate <name>             generate a new XPChain address
        list                        show list for all XPChain addresses
        export <name>               show private key for the XPChain address
        balance                     show balances for all XPChain addresses
        send <name> <to> <amount>   transfer coins to the XPChain address

## Dependencies

* Ruby >= 2.0.0

## Disclaimer

XPChain用に何か作るための自己学習用なので、このソースを使っておかしなことになっても知らぬ。
あと、メインネットで使うとかバカなことはやめるんだ。

## License

The MIT License (MIT)

Copyright (c) 2014 peryaudo (original)
          (c) 2018 naomi-mcrn (modified)

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

