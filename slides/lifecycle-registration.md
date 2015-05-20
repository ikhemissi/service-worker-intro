##  Lifecycle - registration

* Registration is URL-scoped : many SW on a domain but only one per url scope

* Default scope is "/*" but can it overridden in the options of [navigator.serviceWorker.register()](https://developer.mozilla.org/en-US/docs/Web/API/ServiceWorkerContainer/register)

* Service workers are relative to origin, ... not tabs