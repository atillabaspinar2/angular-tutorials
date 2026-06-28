# Angular Tutorial Notes

Personal notes and tutorials covering Angular from core concepts to advanced topics, written against modern Angular (17–21+) with signals, standalone components, and zoneless change detection.

---

## Tutorials

| # | File | Topics |
| --- | --- | --- |
| 01 | [Core Concepts](tutorials/01.core.md) | Interpolation, property/event binding, signals, `@for`, `@if`, two-way binding, services, DI, pipes |
| 02 | [Modules](tutorials/02.modules.md) | NgModules vs standalone components, `imports`, `providers`, module-based bootstrapping |
| 03 | [Component Selectors, Projection, and Host](tutorials/03.component-selectors-projection-and-host.md) | Attribute/class selectors, `ng-content` slots, view encapsulation, `:host`, host bindings |
| 04 | [Class and Style Binding](tutorials/04.class-style-binding.md) | `[class.x]`, `[class]` object, `[style.x]`, `[style]` object, Tailwind coexistence |
| 05 | [Lifecycle Hooks](tutorials/05.lifescycles.md) | All 8 hooks, constructor vs `ngOnInit`, `DestroyRef`, `takeUntilDestroyed` |
| 06 | [Forms](tutorials/06.forms.md) | Template-driven forms, `ngModel`, `NgForm`, `@ViewChild`, `viewChild()`, `@ContentChild` |
| 07 | [Signals and Effects](tutorials/07.signals-effects.md) | `signal`, `computed`, `effect`, reactive context, `untracked`, RxJS interop, `input`/`model`/`output`, React comparison |
| 08 | [Directives](tutorials/08.Directives.md) | Built-in vs custom directives, host events, directive inputs and aliases, service injection, `hostDirectives` |
| 09 | [Pipes](tutorials/09.Pipes.md) | Built-in pipes, parameters, chaining, `async` pipe, custom pipes, pure vs impure |
| 10 | [Dependency Injection](tutorials/10.DependencyInjection.md) | `inject()`, `providedIn`, hierarchical injectors, `InjectionToken`, tree-shakable services |
| 11 | [Change Detection](tutorials/11.ChangeDetection.md) | Zone.js, `OnPush` strategy, `ChangeDetectorRef`, `NgZone`, zoneless mode with signals |
| 12 | [HTTP](tutorials/12.Http.md) | `HttpClient`, GET/POST/PUT/DELETE, `catchError`, `finalize`, service patterns, interceptors, `toSignal` |
| 13 | [Reactive Forms](tutorials/13.FormHandling.md) | `FormGroup`, `FormControl`, validators, `ReactiveFormsModule`, form state and errors |
| 14 | [Routing](tutorials/14.Routing.md) | `RouterModule`, route configuration, lazy loading, guards, `ActivatedRoute`, `Router` |
