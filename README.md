# RAID Configuration Selector

The RAID Configuration Selector is a simple web app that helps users determine which RAID configurations are applicable based on the number of drives they have. It provides a user-friendly interface to input the number of drives and select RAID options, and it displays the compatible RAID configurations.

## Usage

1. Open the `index.html` file in a web browser.
2. Enter the number of drives you have in the "Number of Drives" input field.
3. Check the RAID configurations you want to consider.
4. Click the "Check RAID Configurations" button.
5. The app will display a list of RAID configurations that are compatible with the provided drive count.

## Supported RAID Configurations

- RAID 0 (Striping)
- RAID 1 (Mirroring)
- RAID 5 (Striping with Parity)
- RAID 10 (Combination of RAID 1 and RAID 0)

## Example

Suppose you have 3 drives. By entering "3" and checking the appropriate RAID configurations, the app will inform you that RAID 0 and RAID 1 are applicable for your setup.

## Contributing

Feel free to contribute to this project by creating pull requests or reporting issues. You can suggest enhancements, bug fixes, or additional features.

## License

This project is licensed under the MIT License - see the [LICENSE](./LICENSE) file for details.

## Acknowledgments

- The project uses HTML, CSS, and JavaScript.
