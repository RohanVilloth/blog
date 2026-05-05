This is the source repo for my personal blog. For creating this blog, I followed [Five Minutes to Your Own Website](https://towardsdatascience.com/five-minutes-to-your-own-website-fd0b43cbd886) and forked [Jekyll Now repository](https://github.com/barryclark/jekyll-now).

## Setup Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/RohanVilloth/blog.git
cd blog
```

### 2. Install Dependencies
This project uses Bundler for dependency management.
```bash
# Install Bundler if you don't have it
gem install bundler

# Install project dependencies
bundle install
```

### 3. Start the Jekyll Server
```bash
bundle exec jekyll serve
```
The server will start at `http://localhost:4000`.