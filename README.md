# OpenTelemetry Inspection

Dieses Repository enthält den gesamten Code, sowie alle Konfigurationsdateien, die für die Bachelorarbeit "Einsatz des OpenTelemetry Observability Standards in der Generali Deutschland AG" relevant sind.

## OpenTelemetry Kubernetes Operator

Die in der Bachelorarbeit stattgefundenen Untersuchungen zu dem OpenTelemetry Operator sind in dem Verzeichnis "oteloperator" zu finden. Die in in diesem Zusammenhang
untersuchte Anwendung Google Microservice Demo, sowie die dazugehörigen Helm-Charts sind in dem Verzeichnis "microservices-demo-main" zu finden.

Bemerkung zu den Helm Charts der Google Microservice Demo App: Es sind zwei Versionen des Helm-Charts zu finden. In der originellen ist die OpenTelemetry
Instrumentierung mit dem Operator nicht inkludiert. In dem modifizierten Helm-Chart wurden die notwendigen OpenTelemetry Annotations bei den einzelnen Microservices
eingefügt, sodass die Automatische Injezierung durchgeführt wird.

## Aufbau K8s Cluster

Die Vagrant- und Shell-Skripte für den Aufbau des K8s Clusters sind in dem Verzeichnis "vagrant_setup" zu finden.

## OpenTelemetry Demo App

Der Source Code ist unverändert zu der originellen OpenTelemetry Demo App in dem Verzeichnis "opentelemetry-demo-main" zu finden.
Zusätzlich wurden auch die Helm-Charts hinzugefügt, über die die Anwendung im Cluster deployed werden kann.

## Video

For the video visit: