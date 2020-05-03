# My zshrc dotfiles

Enjoy the tweaks

Powerlevel9k / Powerlevel10k themes

Powerlevel10k comes with a configuration setup - Run the command: `p10k configure`
It gives a list of options which one may choose to get a desired appearance.

It generates .p10k.zsh file in which one can make changes and setup their own configurations.

Hope you'll enjoy it.


<h2>How to use it?</h2>

1. Install Oh My Zsh framework to manage zsh configurations:
    sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"

2. Install powerlevel10k theme:
    git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/themes/powerlevel10k

3. Also download the Meslo font. Link is available on the powerlevel10k github repository
    https://github.com/romkatv/powerlevel10k

4. Change the font to Meslo in the preferences tab of the terminal(I'm using tilix here)

5. Install the autosuggestions extension as well
    git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions

6. Run the command : `p10k configure`. It creates a file .p10.zsh

7. Replace the content of the above created file with the p10k.zsh file provided in this repository.

8. Final command - `source .p10k.zsh`

Now you are good to go.