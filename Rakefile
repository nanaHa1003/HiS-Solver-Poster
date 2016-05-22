task :default => [:compile]

task :compile => "poster.tex" do
  sh "xelatex -interaction=nonstopmode poster.tex" 
end

task :debug => "poster.tex" do
  sh "xelatex poster.tex"
end
