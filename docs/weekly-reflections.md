# Weekly Reflections

## Block 1

### Github Auth

- When I went to push my first updated I was getting prompted to log into github. I ened up using AI to help and as I am using Homebrew I was prompted to use the **gh** package. I installed it and authenthicated with it. I was able to connect my SSH key to it but still had an error with my push. The break through came from running 
> gh auth setup-git
This is what was able to make things work flawlessly.