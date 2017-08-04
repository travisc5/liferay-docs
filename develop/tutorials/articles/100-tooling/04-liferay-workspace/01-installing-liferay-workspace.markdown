# Installing Liferay Workspace [](id=installing-liferay-workspace)

You can install Liferay Workspace using the Liferay Workspace installer. This
installs JPM and
[Blade CLI](/develop/tutorials/-/knowledge_base/7-0/blade-cli) into your user
home folder and optionally initializes a Liferay Workspace folder. This is the
same installer used to install Blade CLI, which is covered in the
[Installing Blade CLI](/develop/tutorials/-/knowledge_base/7-0/installing-blade-cli)
tutorial.

Follow the steps below to download and install Liferay Workspace:

1.  Download the
    [Liferay Workspace installer](https://sourceforge.net/projects/lportal/files/Liferay%20Workspace)
    that corresponds with your operating system (e.g., Windows, MacOS, or
    Linux).

2.  Run the installer. Click *Next* to step through the installer's
    introduction.

3.  Set the directory where your Liferay Workspace should be initialized.

    ![Figure 1: Determine where your Liferay Workspace should reside.](../../../images/blade-installer-workspace-init.png)

    Then click *Next*.

4.  Choose the Liferay product type you intend to use with the workspace. Then
    click *Next*.

    ![Figure 2: Select the product version you'll use with your Liferay Workspace.](../../../images/installer-workspace-type.png)

    +$$$

    **Note:** You'll be prompted for your liferay.com username and password
    before downloading the Liferay DXP bundle. Your credentials are not saved
    locally; they're saved as a token in the `~/.liferay` folder. The token is
    used by your workspace if you ever decide to redownload a DXP bundle.
    Furthermore, the bundle that is downloaded in your workspace is also copied
    to your `~/.liferay/bundles` folder, so if you decide to initialize another
    @product@ instance of the same version, the bundle is not re-downloaded. See
    the
    [Adding a Liferay Bundle to a Workspace](/develop/tutorials/-/knowledge_base/7-0/configuring-a-liferay-workspace#adding-a-liferay-bundle-to-a-workspace)
    for more information on this topic.

    $$$

    **Important:** The `~/.liferay` folder must exist on your machine before
    installing Liferay Workspace. The installer expects this folder to exist,
    and without it, the installer cannot create your token to store your Liferay
    credentials. This is a bug and will be fixed in the next release of the
    Workspace installer.

5.  Click *Next* to begin installing Liferay Workspace on your machine.

That's it! Liferay Workspace is now installed on your machine!
