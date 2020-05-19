gtg_gtk_sources = [
  '__init__.py',
  'application.py',
  'colors.py',
  'general_preferences.py',
  'plugins.py',
  'preferences.py',
  'tag_completion.py',
]

gtg_backend_sources = [
  'backends/__init__.py',
  'backends/addpanel.py',
  'backends/backendscombo.py',
  'backends/backendstree.py',
  'backends/configurepanel.py',
]

gtg_backend_parameters_ui_sources = [
  'backends/parameters_ui/__init__.py',
  'backends/parameters_ui/checkbox.py',
  'backends/parameters_ui/import_tags.py',
  'backends/parameters_ui/password.py',
  'backends/parameters_ui/path.py',
  'backends/parameters_ui/period.py',
  'backends/parameters_ui/text.py',
]

gtg_browser_sources = [
  'browser/__init__.py',
  'browser/backend_infobar.py',
  'browser/cell_renderer_tags.py',
  'browser/delete_tag.py',
  'browser/delete_task.py',
  'browser/main_window.py',
  'browser/modify_tags.py',
  'browser/simple_color_selector.py',
  'browser/tag_context_menu.py',
  'browser/tag_editor.py',
  'browser/treeview_factory.py',
]

gtg_data_sources = [
  'data/backends.ui',
  'data/calendar.ui',
  'data/context_menus.ui',
  'data/general_preferences.ui',
  'data/help_overlay.ui',
  'data/main_window.ui',
  'data/modify_tags.ui',
  'data/plugins.ui',
  'data/preferences.ui',
  'data/style.css',
  'data/task_editor.ui',
]

gtg_editor_sources = [
  'editor/__init__.py',
  'editor/calendar.py',
  'editor/editor.py',
  'editor/serialize.py',
  'editor/taskview.py',
]

python3.install_sources(gtg_gtk_sources, subdir: 'GTG' / 'gtk')
python3.install_sources(gtg_backend_sources, subdir: 'GTG' / 'gtk' / 'backends')
python3.install_sources(gtg_backend_parameters_ui_sources, subdir: 'GTG' / 'gtk' / 'backends' / 'parameters_ui')
python3.install_sources(gtg_browser_sources, subdir: 'GTG' / 'gtk' / 'browser')
python3.install_sources(gtg_data_sources, subdir: 'GTG' / 'gtk' / 'data')
python3.install_sources(gtg_editor_sources, subdir: 'GTG' / 'gtk' / 'editor')