This monorepo hosts unofficial rush plugins created and used inside ByteDance.

# rush-init-project-plugin

When you want to create a new project in your monorepo. There are highly chances you need copy and paste from a project already inside your monorepo. Why not reuse them, like create a project template and used in your monorepo. Yes, `rush-init-project-plugin` is for you!

[Portal](./rush-plugins/rush-init-project-plugin/README.md)

# rush-upgrade-self-plugin

When you maintain a Rush.js managed monorepo, and you write some toolkit based on rush related module, such as `microsoft/rush-lib`, `@rushstack/node-core-library`. Things become trivial if you want to upgrade Rush.js to latest version. You need keep the versions of those dependencies in consistency. `rush-upgrade-self-plugin` comes into rescue, it aims to help you upgrade/downgrade Rush.js version in one line.

[Portal](./rush-plugins/rush-upgrade-self-plugin/README.md)

# rush-archive-project-plugin

After you have tons of project in monorepo, install time gets slower, manage dependencies becomes harder, while some projects are eventually inactive. You just want a way to archive projects properly, and maybe retrieve one day :)
Now, it's time to give this plugin a try!

[Portal](./rush-plugins/rush-archive-project-plugin/README.md)
