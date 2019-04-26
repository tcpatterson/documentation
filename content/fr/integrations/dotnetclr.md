---
categories:
  - languages
creates_events: false
ddtype: check
dependencies:
  - 'https://github.com/DataDog/integrations-core/blob/master/dotnetclr/README.md'
display_name: .NET CLR
git_integration_title: dotnetclr
guid: 3d21557e-65bd-4b66-99b9-5521f32b5957
integration_id: dotnetclr
integration_title: .NET CLR
is_public: true
kind: integration
maintainer: help@datadoghq.com
manifest_version: 1.0.0
metric_prefix: dotnetclr.
metric_to_check: dotnetclr.memory.time_in_gc
name: dotnetclr
public_title: Intégration Datadog/.NET CLR
short_description: Visualiser et surveiller les états de Dotnetclr
support: core
supported_os:
  - windows
---
## Présentation

Recueillez des métriques du service Dotnetclr en temps réel pour :

* Visualiser et surveiller les états de Dotnetclr
* Être informé des failovers et des événements de Dotnetclr.

## Installation

Le check Dotnetclr est inclus avec le paquet de l'[Agent Datadog][1] : vous n'avez donc rien d'autre à installer sur vos serveurs.

## Configuration

1. Modifiez le fichier `dotnetclr.d/conf.yaml` dans le dossier `conf.d/` à la racine du [répertoire de configuration de votre Agent][2] pour commencer à recueillir vos données de performance Dotnetclr.
    Consultez le [fichier d'exemple dotnetclr.d/conf.yaml][3] pour découvrir toutes les options de configuration disponibles.

2. [Redémarrez l'Agent][4].

## Validation

[Lancez la sous-commande `status` de l'Agent][3] et cherchez `dotnetclr` dans la section Checks.

## Dépannage
Besoin d'aide ? Contactez [l'assistance Datadog][5].

[1]: https://app.datadoghq.com/account/settings#agent
[2]: https://docs.datadoghq.com/fr/agent/guide/agent-configuration-files/?tab=agentv6#agent-configuration-directory
[3]: https://docs.datadoghq.com/fr/agent/guide/agent-commands/?tab=agentv6#agent-status-and-information
[4]: https://docs.datadoghq.com/fr/agent/guide/agent-commands/?tab=agentv6#start-stop-and-restart-the-agent
[5]: https://docs.datadoghq.com/fr/help


{{< get-dependencies >}}