# KubeVela Website
[kubevela.io](https://kubevela.io)

## Contributing

- Fork and clone

  ```
  $ git clone git@github.com:xxx/kubevela.io.git
  $ cd kubevela.io
  ```

- Make your changes

  If you would like to override the default css of Jekyll, please revise [./assets/main.scss](./assets/main.scss)

- Build static files

  Generate static files into folder `docs` which will be the source for Github Pages.
  The following command uses [bundler](https://bundler.io/).

  ```
  $ bundle exec jekyll build -d docs
  Configuration file: /Users/zhouzhengxi/Programming/golang/src/github.com/zzxwill/kubevela.io/_config.yml
              Source: /Users/zhouzhengxi/Programming/golang/src/github.com/zzxwill/kubevela.io
         Destination: /Users/zhouzhengxi/Programming/golang/src/github.com/zzxwill/kubevela.io/docs
   Incremental build: disabled. Enable with --incremental
        Generating...
         Jekyll Feed: Generating feed for posts
                      done in 0.11 seconds.
   Auto-regeneration: disabled. Use --watch to enable.
  ```

- Local preview
  ```
  $ bundle exec jekyll serve --livereload -t
  Configuration file: /Users/zhouzhengxi/Programming/golang/src/github.com/zzxwill/kubevela.io/_config.yml
              Source: /Users/zhouzhengxi/Programming/golang/src/github.com/zzxwill/kubevela.io
         Destination: /Users/zhouzhengxi/Programming/golang/src/github.com/zzxwill/kubevela.io/_site
   Incremental build: disabled. Enable with --incremental
        Generating...
         Jekyll Feed: Generating feed for posts
                      done in 0.181 seconds.
   Auto-regeneration: enabled for '/Users/zhouzhengxi/Programming/golang/src/github.com/zzxwill/kubevela.io'
  LiveReload address: http://127.0.0.1:35729
      Server address: http://127.0.0.1:4000/
    Server running... press ctrl-c to stop.
  ```

  Preview your changes at [http://127.0.0.1:4000/](http://127.0.0.1:4000/).

- Push your commit

  Thanks for your contribution!
