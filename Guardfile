guard :sass, input: "sass", output: "css"

guard :livereload do
  watch %r{index\.html}
  watch %r{css/main\.css}
end

guard :haml, input: ".", output: [".", "en"] do
  watch %r{.+\.haml}
end