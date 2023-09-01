# @serdarsen's Karabiner Elements Configuration

I'm in the process of creating my own set of keyboard shortcuts to make my Mac usage more similar to Ubuntu. To ensure consistency and organization, I'm following Apple's official [Mac keyboard shortcuts page](https://support.apple.com/en-us/HT201236) for proper naming and categorization.

## Usage

To use my Karabiner Elements configuration, follow these steps:

1. Install and configure Karabiner Elements using one of the following methods:

   - **Official Documentation**: For detailed installation and configuration instructions, refer to the [official documentation: Getting Started](https://karabiner-elements.pqrs.org/docs/getting-started/).

   - **Homebrew (recommended)**: If you prefer using Homebrew, you can install Karabiner Elements with the [Homebrew Formulae: karabiner-elements](https://formulae.brew.sh/cask/karabiner-elements).
     This method simplifies the installation process and keeps your software up-to-date.

Choose the installation method that suits your preference, and proceed with configuring Karabiner Elements according to your needs.

2. Clone this repository to your local machine.

3. Create a backup of the default ~/.config/karabiner/assets folder, but exercise caution: do not delete the entire 'karabiner' directory or the 'karabiner.json' file. Only proceed to delete the 'assets' folder if it contains no essential files. If necessary, you can create a symlink specifically for 'assets/complex_modifications' as demonstrated below.

4. Create a symlink using the following command (replace `~/dev/karabiner/assets` with the actual local path to where you cloned this repository):
   ```sh
   ln -s ~/dev/karabiner/assets ~/.config/karabiner
   ```


For more guidance on creating your custom complex modifications in Karabiner Elements, you can watch this informative video tutorial: [YouTube: How to Create Your Own CUSTOM Complex Modifications in Karabiner-elements](https://www.youtube.com/watch?v=iiSIaMD4vqY).

Feel free to explore and customize the shortcuts to match your preferences and enhance your Mac experience.