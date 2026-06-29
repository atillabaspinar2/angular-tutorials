# Angular Tutorial Notes

A focused reference series for developers who already know Angular. Use it for quick fact-checking, refreshing a concept before a project, or preparing for interviews.

The official Angular documentation is thorough but large — these notes distill the parts that matter for day-to-day development. Together they cover the majority of what you'll encounter in a typical Angular codebase. Each article is a **5–15 minute read**.

Written against modern Angular (17–22+) with signals, standalone components, and zoneless change detection.

---

## Tutorials

| # | File | Topics |
| --- | --- | --- |
| 01 | [Core Concepts](tutorials/01.core.md) | Interpolation, property/event binding, signals, `@for`, `@if`, two-way binding, services, DI, pipes |
| 02 | [Modules](tutorials/02.modules.md) | NgModules vs standalone components, `imports`, `providers`, module-based bootstrapping |
| 03 | [Component Selectors, Projection, and Host](tutorials/03.component-selectors-projection-and-host.md) | Attribute/class selectors, `ng-content` slots, view encapsulation, `:host`, host bindings |
| 04 | [Class and Style Binding](tutorials/04.class-style-binding.md) | `[class.x]`, `[class]` object, `[style.x]`, `[style]` object, Tailwind coexistence |
| 05 | [Lifecycle Hooks](tutorials/05.Lifecycles.md) | All 8 hooks, constructor vs `ngOnInit`, `DestroyRef`, `takeUntilDestroyed` |
| 06 | [Template-Driven Forms](tutorials/06.Forms-basics-and-templateDriven.md) | Template-driven forms, `ngModel`, `NgForm`, form validation, `@ViewChild`, `viewChild()`, `@ContentChild` |
| 07 | [Signals and Effects](tutorials/07.signals-effects.md) | `signal`, `computed`, `effect`, reactive context, `untracked`, RxJS interop, `input`/`model`/`output`, React comparison |
| 08 | [Directives](tutorials/08.Directives.md) | Built-in vs custom directives, host events, directive inputs and aliases, service injection, `hostDirectives` |
| 09 | [Pipes](tutorials/09.Pipes.md) | Built-in pipes, parameters, chaining, `async` pipe, custom pipes, pure vs impure |
| 10 | [Dependency Injection](tutorials/10.DependencyInjection.md) | `inject()`, `@Injectable`, `@Service()` (v22), `providedIn`, component-level providers, `InjectionToken`, `useClass`/`useValue`/`useFactory`, optional injection |
| 11 | [Change Detection](tutorials/11.ChangeDetection.md) | Zone.js, `OnPush` strategy, `ChangeDetectorRef`, `NgZone`, zoneless mode with signals |
| 12 | [HTTP](tutorials/12.Http.md) | `HttpClient`, GET/POST/PUT/DELETE, `catchError`, `finalize`, service patterns, interceptors, `toSignal` |
| 13 | [Reactive Forms](tutorials/13.ReactiveForms.md) | `FormGroup`, `FormControl`, built-in and custom validators, async validators, value changes, programmatic updates |
| 14 | [Routing](tutorials/14.Routing.md) | Setup, `router-outlet`, `routerLink`, route params, `ActivatedRoute`, `snapshot` vs observable, query params, nested routes, resolvers, `runGuardsAndResolvers`, guards (`canActivate`, `canDeactivate`, `canMatch`) |
| 15 | [Deployment](tutorials/15.Deployment.md) | `ng build`, `ng deploy`, SSR with `@angular/ssr`, rendering modes (`Prerender`/`Server`/`Client`), SSR pitfalls |
