[![Releases](https://img.shields.io/badge/releases-purple)](https://github.com/opentelemetry-php/contrib-auto-codeigniter/releases)
[![Issues](https://img.shields.io/badge/issues-pink)](https://github.com/open-telemetry/opentelemetry-php/issues)
[![Source](https://img.shields.io/badge/source-contrib-green)](https://github.com/open-telemetry/opentelemetry-php-contrib/tree/main/src/Instrumentation/CodeIgniter)
[![Mirror](https://img.shields.io/badge/mirror-opentelemetry--php--contrib-blue)](https://github.com/opentelemetry-php/contrib-auto-codeigniter)
[![Latest Version](http://poser.pugx.org/open-telemetry/opentelemetry-auto-codeigniter/v/unstable)](https://packagist.org/packages/open-telemetry/opentelemetry-auto-codeigniter/)
[![Stable](http://poser.pugx.org/open-telemetry/opentelemetry-auto-codeigniter/v/stable)](https://packagist.org/packages/open-telemetry/opentelemetry-auto-codeigniter/)

This is a read-only subtree split of https://github.com/open-telemetry/opentelemetry-php-contrib.

# OpenTelemetry CodeIgniter auto-instrumentation

Please read https://opentelemetry.io/docs/instrumentation/php/automatic/ for instructions on how to
install and configure the extension and SDK.

## Overview

Requires CodeIgniter 4.0+

## Configuration

The extension can be disabled via [runtime configuration](https://opentelemetry.io/docs/instrumentation/php/sdk/#configuration):

```shell
OTEL_PHP_DISABLED_INSTRUMENTATIONS=codeigniter
```
