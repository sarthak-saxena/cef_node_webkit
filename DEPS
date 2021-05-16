hooks = [
  {
    # A change to a .gyp, .gypi, or to GYP itself should run the generator.
    "pattern": ".",
    "action": ["python", "src/cef/tools/gclient_hook.py"],
  },
]

deps = [{
  'src/third_party/WebKit': 'https://chromium.googlesource.com/external/github.com/WebKit/webkit.git'
}]