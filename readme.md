## Node/AWS Development Environment
This is how I keep track of of my global dependencies and to set up new environments on Mac

### Dependencies

> Install XCode first

**This Repo**
git clone https://github.com/pwningcode/development-environment.git

**Homebrew**
```zsh
curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh | bash
```

**Docker**
```zsh
curl "https://download.docker.com/mac/stable/Docker.dmg" -o "Docker.dmg"
./installdmg.sh Docker.dmg
rm -f Docker.dmg
open /Applications/Docker.app
```

**NVM**
```zsh
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.35.3/install.sh | bash
```

**Node**
```zsh
nvm install --lts=dubnium
nvm install --lts=erbium
nvm use default
```

**Yarn**
```zsh
npm install -g yarn
```

**AWS CLI**
```zsh
curl "https://awscli.amazonaws.com/AWSCLIV2.pkg" -o "AWSCLIV2.pkg"
sudo installer -pkg AWSCLIV2.pkg -target /
rm -f AWSCLIV2.pkg
```

**AWS CDK CLI**
```zsh
npm install -g aws-cdk
```

**AWS Amplify CLI**
```zsh
npm install -g @aws-amplify/cli
```

**AWS SAM CLI**
```zsh
brew tap aws/tap
brew install aws-sam-cli
```

**Typescript**
```zsh
npm install -g typescript
```

**VS Code AWS Toolkit**
```zsh
open https://docs.aws.amazon.com/toolkit-for-vscode/latest/userguide/setup-toolkit.html
```

## Installing Development Environment

**Configure AWS CLI**
```zsh
aws configure
```

**Configure AWS AMPLIFY**
```zsh
amplify configure
```
