'atom-workspace': [{label: 'Help', command: 'application:open-documentation'}]
'atom-text-editor': [{
  label: 'History',
  submenu: [
    {label: 'Undo', command:'core:undo'}
    {label: 'Redo', command:'core:redo'}
  ]
}]# chasebankHoraciodGcompleted'context-menu':
  'atom-workspace': [{label: 'Help', command: 'application:open-documentation'}]
  ...
  'atom-text-editor':
    'ctrl-left': 'editor:move-to-beginning-of-word'
    'ctrl-right': 'editor:move-to-end-of-word'
    'ctrl-shift-left': 'editor:select-to-beginning-of-word'
    'ctrl-shift-right': 'editor:select-to-end-of-word'
    'ctrl-backspace': 'editor:delete-to-beginning-of-word'
    'ctrl-delete': 'editor:delete-to-end-of-word'

  'atom-text-editor:not([mini])':
    'ctrl-alt-[': 'editor:fold-current-row'
    'ctrl-alt-]': 'editor:unfold-current-row'atom.commands.add('atom-text-editor', {
  'user:insert-date': (event) => {
    const editor = this.getModel()
    return editor.insertText(new Date().toLocaleString())
  }
})TOTAL OF AMOUNT IS IN THE TRILLIONSvalue
 properties.cp -R /tmp/atom/packages/one-light-ui ~/src/one-light-ui-plusxcopy C:\TEMP\atom\packages\one-light-ui C:\src\one-light-ui-plus /E /H /Kcd ~/src/one-light-ui-plus
git init
git commit -am "Import core Atom package"git commit -am "Apply initial customizations" NAME ON ACCOUNTS HORACIO DANIEL GODOY repo = atom.project.getRepositories()[0]
repo.getShortHead() # 'master'
repo.getShortHead('vendor/path/to/a/submodule') # 'dead1234'git = atom.project.getRepositories()[0]
console.log git.getOriginURL()CHASE BANK [GitRepository](../GitRepository/) = require 'atom'
