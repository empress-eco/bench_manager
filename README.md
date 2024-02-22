<div align="center">
  <img src="https://grow.empress.eco/uploads/default/original/2X/1/1f1e1044d3864269d2a613577edb9763890422ab.png" alt="Bench Manager Logo" width="96">
  <h1 align="center">Bench Manager: Streamline Your App & Site Management</h1>
  <p align="center">
    A user-friendly GUI that mirrors the Bench CLI to facilitate easy app installation, site management, and updates.
    <br />
    <a href="https://github.com/empress-eco/bench_manager/wiki"><strong>Explore the Docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/empress-eco/bench_manager/issues">Report Bug</a>
    ·
    <a href="https://github.com/empress-eco/bench_manager/issues">Request Feature</a>
  </p>
</div>

## About Bench Manager

Bench Manager is an intuitive graphical user interface designed to emulate the functionalities of the Bench command line utility. It is the perfect tool for developers who manage multiple applications and sites, making the process of installation, updates, and management more streamlined and efficient.

### Key Features
- **App and Site Management:** Easily install and update apps, create new apps and sites, and manage multiple sites seamlessly.
- **Backup and Restore:** Ensure the safety of your work with app and site backup capabilities and easily restore backups when needed.
- **Command Logging:** Keep track of your work and troubleshoot easily with command logging.

## Getting Started

### Prerequisites
Before using Bench Manager, ensure you have a running Bench instance.

### Installation
To install Bench Manager, follow these instructions to set it up on a new site called bench-manager.local:

#### Automated Installation (Recommended)
```sh
$ bench setup manager
```
This command will create a new site, obtain the `bench_manager` app from the repository, and install it on the site.

#### Manual Installation
```sh
$ bench new-site bench-manager.local
$ bench get-app bench_manager
$ bench --site bench-manager.local install-app bench_manager
```

### Usage
With Bench Manager installed, you can now manage your apps and sites, update your Bench instance, backup your sites, install/uninstall apps, restore backups, and create new apps and sites.

## Contributing
We invite you to contribute to Bench Manager! Here's how you can do it:

- Fork the Project
- Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
- Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
- Push to the Branch (`git push origin feature/AmazingFeature`)
- Open a Pull Request

## License

This project is licensed under the MIT License. Your contributions are also licensed under the same.

## Acknowledgements

We would like to express our gratitude to the Empress Community for their foundational contributions that power this project. Their innovative tools and steadfast dedication have been instrumental in the creation of Bench Manager. We are deeply appreciative of their pioneering work and ongoing support.

<!-- MARKDOWN LINKS & IMAGES -->
