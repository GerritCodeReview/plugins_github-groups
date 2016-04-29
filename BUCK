include_defs('//bucklets/gerrit_plugin.bucklet')

MODULE = 'com.googlesource.gerrit.plugins.github.groups'

gerrit_plugin(
  name = 'github-groups',
  srcs = glob(['src/main/java/**/*.java']),
  resources = glob(['src/main/**/*']),
  manifest_entries = [
    'Gerrit-PluginName: github-groups',
    'Gerrit-Module: com.googlesource.gerrit.plugins.github.groups.Module',
    'Implementation-Title: GitHub Groups',
    'Implementation-URL: https://gerrit-review.googlesource.com/#/admin/projects/plugins/github-groups',
  ],
)
