gocraft_gorelic
=============

gocraft_gorelic is NewRelic middleware for gocraft framework.

# Installation
 - Run "go get github.com/yvasiyarov/gocraft_gorelic"
 - Add following lines to your main() function:
  gocraft_gorelic.InitNewrelicAgent("7bceac019c7dcafae1ef95be3e3a3ff8866de266", "test gocraft app", true)
  router.Middleware(gocraft_gorelic.Handler)

Please, dont forget to change NewRelic license to your license
