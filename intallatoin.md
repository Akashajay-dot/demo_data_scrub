## trufflehog installation
curl -sSfL https://raw.githubusercontent.com/trufflesecurity/trufflehog/main/scripts/install.sh | sh -s -- -b /usr/local/bin

## homebrew installation
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

## bfg installatoin
brew install bfg

## trufflehog usage 
trufflehog git https://github.com/trufflesecurity/test_keys --results=verified,unknown