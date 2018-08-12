We built a GUI application (using WPF) through which we can communicate with
Service.

Our GUI app will consist of 2 pages that will be stored in Tabs
The transition between the two pages will be by switching between the different tabs.

Each page will be set by UserControl when the main window (MainWindow) will be created
Pages and store them in TabControl.

Each page will be built using the MVVM = Model - ViewModel - View architecture.

The communication between the GUI and the SERVICE will be by opening the TCP communication channel in it
The different messages will follow.

Use EVENTS to communicate between classes.
