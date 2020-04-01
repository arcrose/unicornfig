# Demonstration

Here you can see how we might configure information about some databases a system is using
by writing the configuration in Fig, making it very easy to combine data programattically.

Both the `database.json` and `db.yaml` files in this directory were generated by running
the `database.fig` file with Unicorn from this directory as follows

    ../unicorn -json database.json -yaml db.yaml database.fig

When it comes time to change the configuration you provide, it's very easy now to
change the fig code accordingly and generate the appropriate configuration files.