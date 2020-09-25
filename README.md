## How to install deprecated elasticsearch@5.6 with brew

1. Clone this repo.
2. Make a new tap: `brew tap-new my_local_tap/elasticsearch`
3. Copy the formula to the tap: `cp elasticsearch@5.6.rb /usr/local/Homebrew/Library/Taps/my_loca_tap/homebrew-elasticsearch/Formula/`
4. Tap into the local tap: `brew tap my_loca_tap/elasticsearch`
5. Install: `brew install elasticsearch@5.6`
