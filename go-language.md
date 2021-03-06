# Go Programming Language

## Style and Guidelines

* read [https://github.com/golang/go/wiki/CodeReviewComments](https://github.com/golang/go/wiki/CodeReviewComments)
* format code according to `gofmt`, nothing else will be accepted
* don't use a local include path, always prefix the full package URL "github.com/.../package"
* create functions that return errors as the second return argument and handle it
* use const if possible and multiple const blocks if necessary
* [https://github.com/tmrts/go-patterns](https://github.com/tmrts/go-patterns)
* [https://github.com/cristaloleg/go-advices/blob/master/README.md](https://github.com/cristaloleg/go-advices/blob/master/README.md)

## Books

* The Go Programming Language \(Addison-Wesley Professional Computing Series\) by Alan A. A. Donovan, Brian W. Kernighan 
* [https://github.com/avelino/awesome-go\#e-books](https://github.com/avelino/awesome-go#e-books)
* [https://github.com/dariubs/GoBooks](https://github.com/dariubs/GoBooks)
* [https://github.com/dgryski/go-perfbook](https://github.com/dgryski/go-perfbook)
* [http://shop.oreilly.com/product/0636920046189.do](http://shop.oreilly.com/product/0636920046189.do)
* go-internals [https://github.com/teh-cmc/go-internals](https://github.com/teh-cmc/go-internals)

## Best Practices & interesting articles

* Create object as interface type under the OOP concept, which will benefit in the test for mocking out different objects later on.
* [https://github.com/avelino/awesome-go](https://github.com/avelino/awesome-go)
* [https://golangweekly.com/](https://golangweekly.com/)
* [https://go-proverbs.github.io/](https://go-proverbs.github.io/)
* [https://dave.cheney.net/2016/04/27/dont-just-check-errors-handle-them-gracefully](https://dave.cheney.net/2016/04/27/dont-just-check-errors-handle-them-gracefully)
* [https://peter.bourgon.org/go-best-practices-2016/](https://peter.bourgon.org/go-best-practices-2016/)
* [https://golang.org/doc/effective\_go.html](https://golang.org/doc/effective_go.html)
* [https://medium.com/@teivah/good-code-vs-bad-code-in-golang-84cb3c5da49d](https://medium.com/@teivah/good-code-vs-bad-code-in-golang-84cb3c5da49d)
* [https://github.com/teivah/golang-good-code-bad-code](https://github.com/teivah/golang-good-code-bad-code)
* [https://medium.com/@val\_deleplace/go-code-refactoring-the-23x-performance-hunt-156746b522f7](https://medium.com/@val_deleplace/go-code-refactoring-the-23x-performance-hunt-156746b522f7)
* [https://allegro.tech/2017/07/golang-slices-gotcha.html](https://allegro.tech/2017/07/golang-slices-gotcha.html)
* [https://github.com/matttproud/gochecklist](https://github.com/matttproud/gochecklist)
* [https://talks.golang.org/2013/bestpractices.slide\#1](https://talks.golang.org/2013/bestpractices.slide#1)
* [https://blog.depado.eu/post/checklist-for-go-projects](https://blog.depado.eu/post/checklist-for-go-projects)
* Go Memory Model [https://golang.org/ref/mem](https://golang.org/ref/mem)
* [https://roberto.selbach.ca/intro-to-go-modules/](https://roberto.selbach.ca/intro-to-go-modules/)
* [https://medium.zenika.com/go-1-11-webassembly-for-the-gophers-ae4bb8b1ee03](https://medium.zenika.com/go-1-11-webassembly-for-the-gophers-ae4bb8b1ee03)
* [https://medium.com/percolate-engineering/introducing-charlatan-df9b5d3d3107](https://medium.com/percolate-engineering/introducing-charlatan-df9b5d3d3107)
* [https://itnext.io/debug-a-go-application-in-kubernetes-from-ide-c45ad26d8785](https://itnext.io/debug-a-go-application-in-kubernetes-from-ide-c45ad26d8785)
* [https://github.com/enocom/gopher-reading-list](https://github.com/enocom/gopher-reading-list)
* [http://oyvindsk.com/writing/common-golang-mistakes-1](http://oyvindsk.com/writing/common-golang-mistakes-1)
* [https://eli.thegreenplace.net/2018/go-hits-the-concurrency-nail-right-on-the-head/](https://eli.thegreenplace.net/2018/go-hits-the-concurrency-nail-right-on-the-head/)

## Package Design

* [https://medium.com/@benbjohnson/standard-package-layout-7cdbc8391fc1](https://medium.com/@benbjohnson/standard-package-layout-7cdbc8391fc1)
* [https://github.com/golang-standards/project-layout](https://github.com/golang-standards/project-layout)
* [https://blog.gopheracademy.com/advent-2016/go-and-package-focused-design/](https://blog.gopheracademy.com/advent-2016/go-and-package-focused-design/)
* [https://www.ardanlabs.com/blog/2017/02/package-oriented-design.html](https://www.ardanlabs.com/blog/2017/02/package-oriented-design.html)
* [https://www.reddit.com/r/golang/comments/84a1q6/go\_project\_structure\_is/](https://www.reddit.com/r/golang/comments/84a1q6/go_project_structure_is/)
* [https://peter.bourgon.org/go-best-practices-2016/\#repository-structure](https://peter.bourgon.org/go-best-practices-2016/#repository-structure)
* [https://medium.com/statuscode/how-i-write-go-http-services-after-seven-years-37c208122831](https://medium.com/statuscode/how-i-write-go-http-services-after-seven-years-37c208122831)
* [https://dave.cheney.net/2016/08/20/solid-go-design](https://dave.cheney.net/2016/08/20/solid-go-design)

## Tutorials

* For starter: [https://tour.golang.org/welcome/1](https://tour.golang.org/welcome/1)
* More [https://github.com/avelino/awesome-go\#tutorials](https://github.com/avelino/awesome-go#tutorials)
* [https://github.com/golang/go/wiki/Learn](https://github.com/golang/go/wiki/Learn)
* Cheatsheet [https://github.com/a8m/go-lang-cheat-sheet](https://github.com/a8m/go-lang-cheat-sheet)
* [https://grpc.io/docs/tutorials/basic/go.html](https://grpc.io/docs/tutorials/basic/go.html)
* [https://gobyexample.com/](https://gobyexample.com/)

## Tests

* [https://medium.com/@povilasve/go-advanced-tips-tricks-a872503ac859](https://medium.com/@povilasve/go-advanced-tips-tricks-a872503ac859)
* [https://medium.com/@sebdah/go-best-practices-testing-3448165a0e18](https://medium.com/@sebdah/go-best-practices-testing-3448165a0e18)
* [https://github.com/stretchr/testify](https://github.com/stretchr/testify)
* [https://github.com/vektra/mockery](https://github.com/vektra/mockery)
* [https://plugins.jetbrains.com/plugin/10460-golang-mockery](https://plugins.jetbrains.com/plugin/10460-golang-mockery)
* [https://github.com/smartystreets/goconvey](https://github.com/smartystreets/goconvey) and [http://goconvey.co/](http://goconvey.co/)
* [https://onsi.github.io/ginkgo/](https://onsi.github.io/ginkgo/) 
* [https://onsi.github.io/gomega/](https://onsi.github.io/gomega/)
* [https://blog.codeship.com/testing-in-go/](https://blog.codeship.com/testing-in-go/)
* [https://medium.com/agrea-technogies/mocking-dependencies-in-go-bb9739fef008](https://medium.com/agrea-technogies/mocking-dependencies-in-go-bb9739fef008)

## Architecture & DDD

* go-kit & microservices [https://www.youtube.com/watch?v=NX0sHF8ZZgw](https://www.youtube.com/watch?v=NX0sHF8ZZgw)
* [https://github.com/bxcodec/go-clean-arch](https://github.com/bxcodec/go-clean-arch)
* [https://www.joeldholmes.com/post/go-hex-arch/](https://www.joeldholmes.com/post/go-hex-arch/)
* [https://medium.com/@eminetto/clean-architecture-using-golang-b63587aa5e3f](https://medium.com/@eminetto/clean-architecture-using-golang-b63587aa5e3f)
* [https://hackernoon.com/trying-clean-architecture-on-golang-2-44d615bf8fdf](https://hackernoon.com/trying-clean-architecture-on-golang-2-44d615bf8fdf)
* [https://manuel.kiessling.net/2012/09/28/applying-the-clean-architecture-to-go-applications/](https://manuel.kiessling.net/2012/09/28/applying-the-clean-architecture-to-go-applications/)
* [https://hackernoon.com/golang-clean-archithecture-efd6d7c43047](https://hackernoon.com/golang-clean-archithecture-efd6d7c43047)
* clean arch validator [https://github.com/roblaszczak/go-cleanarch](https://github.com/roblaszczak/go-cleanarch)
* [https://gist.github.com/eduncan911/c1614e684e4802d626ae](https://gist.github.com/eduncan911/c1614e684e4802d626ae)
* [https://threedots.tech/post/microservices-or-monolith-its-detail](https://threedots.tech/post/microservices-or-monolith-its-detail)
* [https://hackernoon.com/golang-clean-archithecture-efd6d7c43047](https://hackernoon.com/golang-clean-archithecture-efd6d7c43047)
* [https://medium.com/@eminetto/clean-architecture-using-golang-b63587aa5e3f](https://medium.com/@eminetto/clean-architecture-using-golang-b63587aa5e3f)
* [https://juicemia.com/post/go-ddd/](https://juicemia.com/post/go-ddd/)
* [https://www.citerus.se/go-ddd/](https://www.citerus.se/go-ddd/)
* [https://outcrawl.com/go-microservices-cqrs-docker/](https://outcrawl.com/go-microservices-cqrs-docker/)
* [https://github.com/marcusolsson/goddd](https://github.com/marcusolsson/goddd)
* [https://www.youtube.com/watch?v=dPmqQqPn75w](https://www.youtube.com/watch?v=dPmqQqPn75w)
* [Criticism](https://www.reddit.com/r/golang/comments/6ugzo2/domain_driven_design_and_go/dlsm85q)

## Performance & monitoring

* [https://blog.golang.org/profiling-go-programs](https://blog.golang.org/profiling-go-programs)
* [https://jvns.ca/blog/2017/09/24/profiling-go-with-pprof/](https://jvns.ca/blog/2017/09/24/profiling-go-with-pprof/)
* [https://github.com/google/pprof](https://github.com/google/pprof)
* [https://golang.org/pkg/net/http/pprof/](https://golang.org/pkg/net/http/pprof/)
* go-perfbook [https://github.com/dgryski/go-perfbook](https://github.com/dgryski/go-perfbook)
* [https://golang.org/pkg/net/http/pprof/](https://golang.org/pkg/net/http/pprof/)
* Command line monitoring for goroutines [https://github.com/bcicen/grmon](https://github.com/bcicen/grmon)
* A tool to list and diagnose Go processes currently running on your system [https://github.com/google/gops](https://github.com/google/gops)

## Libraries

* [https://github.com/kgoralski?language=go&tab=stars](https://github.com/kgoralski?language=go&tab=stars)
* [https://github.com/golangci/awesome-go-linters](https://github.com/golangci/awesome-go-linters)
* [https://github.com/kisielk/errcheck](https://github.com/kisielk/errcheck)
* [https://github.com/sirupsen/logrus](https://github.com/sirupsen/logrus)

## Go and Rx \(Reactive\) Extensions

Do we need it for Go? We have channels and goroutines.

* [https://github.com/ReactiveX/RxGo](https://github.com/ReactiveX/RxGo)
* [https://medium.com/@jochasinga/go-reactivex-programming-4a2d5e077ce9](https://medium.com/@jochasinga/go-reactivex-programming-4a2d5e077ce9)
* [https://www.reddit.com/r/golang/comments/5rskwd/rxgo\_port\_of\_reactivex\_observable\_stream\_to\_go/](https://www.reddit.com/r/golang/comments/5rskwd/rxgo_port_of_reactivex_observable_stream_to_go/)
* [https://forum.golangbridge.org/t/chans-goroutines-vs-reactive-extensions/1251](https://forum.golangbridge.org/t/chans-goroutines-vs-reactive-extensions/1251)
* [https://github.com/trustmaster/goflow](https://github.com/trustmaster/goflow)
* Why this is important for Java [https://spring.io/blog/2016/06/07/notes-on-reactive-programming-part-i-the-reactive-landscape](https://spring.io/blog/2016/06/07/notes-on-reactive-programming-part-i-the-reactive-landscape) "What is driving the rise of Reactive in Enterprise Java? Well, it’s not \(all\) just a technology fad — people jumping on the bandwagon with the shiny new toys. The driver is efficient resource utilization, or in other words, spending less money on servers and data centres. The promise of Reactive is that you can do more with less, specifically you can process higher loads with fewer threads. This is where the intersection of Reactive and non-blocking, asynchronous I/O comes to the foreground. For the right problem, the effects are dramatic. For the wrong problem, the effects might go into reverse \(you actually make things worse\). Also remember, even if you pick the right problem, there is no such thing as a free lunch, and Reactive doesn’t solve the problems for you, it just gives you a toolbox that you can use to implement solutions." 

## IDE

* [https://www.jetbrains.com/go/](https://www.jetbrains.com/go/)
* [https://plugins.jetbrains.com/plugin/10460-golang-mockery](https://plugins.jetbrains.com/plugin/10460-golang-mockery)
* File Watchers [https://www.jetbrains.com/help/go/settings-tools-file-watchers.html](https://www.jetbrains.com/help/go/settings-tools-file-watchers.html)
* [https://github.com/fatih/vim-go](https://github.com/fatih/vim-go)
* [https://farazdagi.com/blog/2015/vim-as-golang-ide/](https://farazdagi.com/blog/2015/vim-as-golang-ide/)
* [https://github.com/derekparker/delve](https://github.com/derekparker/delve)
* [https://code.visualstudio.com/docs/languages/go](https://code.visualstudio.com/docs/languages/go)
* [https://blog.jetbrains.com/idea/2018/03/intellij-idea-2018-1-kubernetes-support/](https://blog.jetbrains.com/idea/2018/03/intellij-idea-2018-1-kubernetes-support/)
* [https://plugins.jetbrains.com/plugin/7371-aws-cloudformation](https://plugins.jetbrains.com/plugin/7371-aws-cloudformation)
* [https://plugins.jetbrains.com/plugin/7808-hashicorp-terraform--hcl-language-support](https://plugins.jetbrains.com/plugin/7808-hashicorp-terraform--hcl-language-support)
* [https://github.com/amix/vimrc](https://github.com/amix/vimrc)

## Go for Java devs

* [https://github.com/fstab/go-programming-for-java-developers](https://github.com/fstab/go-programming-for-java-developers)
* [https://steveperkins.com/go-for-java-programmers/](https://steveperkins.com/go-for-java-programmers/)
* [https://yourbasic.org/golang/go-java-tutorial/](https://yourbasic.org/golang/go-java-tutorial/)

