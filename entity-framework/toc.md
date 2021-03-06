# [Entity Framework](index.md)

## [Vergleichen von EF Core und EF 6](efcore-and-ef6/index.md)

### [Auswählen des richtigen Leitfadens](efcore-and-ef6/choosing.md)
### [Featurevergleich](efcore-and-ef6/features.md)
### [EF 6 und EF Core in derselben Anwendung](efcore-and-ef6/side-by-side.md)
### [Portieren von EF 6 nach EF Core](efcore-and-ef6/porting/index.md)
#### [Überprüfen von Anforderungen](efcore-and-ef6/porting/ensure-requirements.md)
#### [Portieren eines EDMX-basierten Modells](efcore-and-ef6/porting/port-edmx.md)
#### [Portieren eines codebasierten Modells](efcore-and-ef6/porting/port-code.md)

## [Entity Framework Core](core/index.md)

### [Neuigkeiten](core/what-is-new/index.md)
#### [EF Core Roadmap](core/what-is-new/roadmap.md)
#### [EF Core 2.1](core/what-is-new/ef-core-2.1.md)
#### [EF Core 2.0](core/what-is-new/ef-core-2.0.md)
#### [EF Core 1.1](core/what-is-new/ef-core-1.1.md)
#### [EF Core 1.0](core/what-is-new/ef-core-1.0.md)

### [Erste Schritte](core/get-started/index.md)
#### [Installieren von EF Core](core/get-started/install/index.md)
#### [.NET Framework (Konsole, Windows Forms, WPF etc.)](core/get-started/full-dotnet/index.md)
##### [.NET Framework – Neue Datenbank](core/get-started/full-dotnet/new-db.md)
##### [.NET Framework – Vorhandene Datenbank](core/get-started/full-dotnet/existing-db.md)
#### [.NET Core (Windows, OS X, Linux etc.)](core/get-started/netcore/index.md)
##### [.NET Core – Neue Datenbank](core/get-started/netcore/new-db-sqlite.md)
#### [ASP.NET Core](core/get-started/aspnetcore/index.md)
##### [ASP.NET Core – Neue Datenbank](core/get-started/aspnetcore/new-db.md)
##### [ASP.NET Core – Vorhandene Datenbank](core/get-started/aspnetcore/existing-db.md)
##### [⤤ EF Core und Razor Pages](/aspnet/core/data/ef-rp/intro)
#### [Universelle Windows-Plattform (UWP)](core/get-started/uwp/index.md)
##### [UWP – Neue Datenbank](core/get-started/uwp/getting-started.md)

### [Erstellen eines Modells](core/modeling/index.md)
#### [Einschließen und Ausschließen von Typen](core/modeling/included-types.md)
#### [Einschließen und Ausschließen von Eigenschaften](core/modeling/included-properties.md)
#### [Schlüssel (primär)](core/modeling/keys.md)
#### [Generierte Werte](core/modeling/generated-properties.md)
#### [Erforderliche bzw. optionale Eigenschaften](core/modeling/required-optional.md)
#### [Maximale Länge](core/modeling/max-length.md)
#### [Parallelitätstokens](core/modeling/concurrency.md)
#### [Schatteneigenschaften](core/modeling/shadow-properties.md)
#### [Beziehungen](core/modeling/relationships.md)
#### [Indizes](core/modeling/indexes.md)
#### [Alternativschlüssel](core/modeling/alternate-keys.md)
#### [Vererbung](core/modeling/inheritance.md)
#### [Unterstützungsfelder](core/modeling/backing-field.md)
#### [Wertkonvertierungen](core/modeling/value-conversions.md)
#### [Datenseeding](core/modeling/data-seeding.md)
#### [Entitätstypkonstruktoren](core/modeling/constructors.md)
#### [Entitätstypen im Besitz](core/modeling/owned-entities.md)
#### [Abfragetypen](core/modeling/query-types.md)
#### [Alternierende Modelle mit demselben DbContext-Typ](core/modeling/dynamic-model.md)
#### [Modellierung relationaler Datenbanken](core/modeling/relational/index.md)
##### [Tabellenzuordnung](core/modeling/relational/tables.md)
##### [Spaltenzuordnung](core/modeling/relational/columns.md)
##### [Datentypen](core/modeling/relational/data-types.md)
##### [Primärschlüssel](core/modeling/relational/primary-keys.md)
##### [Standardschema](core/modeling/relational/default-schema.md)
##### [Berechnete Spalten](core/modeling/relational/computed-columns.md)
##### [Sequenzen](core/modeling/relational/sequences.md)
##### [Standardwerte](core/modeling/relational/default-values.md)
##### [Indizes](core/modeling/relational/indexes.md)
##### [Fremdschlüsseleinschränkungen](core/modeling/relational/fk-constraints.md)
##### [Alternativschlüssel (Unique-Einschränkungen)](core/modeling/relational/unique-constraints.md)
##### [Vererbung (relationale Datenbank)](core/modeling/relational/inheritance.md)

### [Verwalten von Datenbankschemas](core/managing-schemas/index.md)
#### [Migrationen](core/managing-schemas/migrations/index.md)
##### [Teamumgebungen](core/managing-schemas/migrations/teams.md)
##### [Benutzerdefinierte Vorgänge](core/managing-schemas/migrations/operations.md)
##### [Verwenden eines separaten Projekts](core/managing-schemas/migrations/projects.md)
##### [Mehrere Anbieter](core/managing-schemas/migrations/providers.md)
##### [Benutzerdefinierte Verlaufstabelle](core/managing-schemas/migrations/history-table.md)
#### [🔧 Erstellen und Löschen von APIs](core/managing-schemas/ensure-created.md)
#### [🔧 Reverse Engineering](core/managing-schemas/scaffolding.md)

### [Abfragen von Daten](core/querying/index.md)
#### [Grundlegende Abfrage](core/querying/basic.md)
#### [Laden von relevanten Daten](core/querying/related-data.md)
#### [Client- vs. Serverauswertung](core/querying/client-eval.md)
#### [Abfragen mit Nachverfolgung vs. ohne Nachverfolgung](core/querying/tracking.md)
#### [Leere SQL-Abfragen](core/querying/raw-sql.md)
#### [Asynchrone Abfragen](core/querying/async.md)
#### [Funktionsweise von Abfragen](core/querying/overview.md)
#### [Globale Abfragefilter](core/querying/filters.md)

### [Speichern von Daten](core/saving/index.md)
#### [Grundlegender Speichervorgang](core/saving/basic.md)
#### [Relevante Daten](core/saving/related-data.md)
#### [Kaskadierendes Delete](core/saving/cascade-delete.md)
#### [Parallelitätskonflikte](core/saving/concurrency.md)
#### [Transaktionen](core/saving/transactions.md)
#### [Asynchroner Speichervorgang](core/saving/async.md)
#### [Getrennte Entitäten](core/saving/disconnected-entities.md)
#### [Explizite Werte für generierte Eigenschaften](core/saving/explicit-values-generated-properties.md)

### [Unterstützte .NET-Implementierungen](core/platforms/index.md)

### [Datenbankanbieter](core/providers/index.md)
#### [Microsoft SQL Server](core/providers/sql-server/index.md)
##### [Speicheroptimierte Tabellen](core/providers/sql-server/memory-optimized-tables.md)
#### [SQLite](core/providers/sqlite/index.md)
##### [SQLite-Einschränkungen](core/providers/sqlite/limitations.md)
#### [InMemory (für Tests)](core/providers/in-memory/index.md)
#### [Schreiben eines Datenbankanbieters](core/providers/writing-a-provider.md)
#### [Änderungen mit Auswirkungen auf den Anbieter](core/providers/provider-log.md)

### [Tools und Erweiterungen](core/extensions/index.md)

### [MSBuild-Befehlszeilenreferenz](core/miscellaneous/cli/index.md)
#### [Paket-Manager-Konsole (Visual Studio)](core/miscellaneous/cli/powershell.md)
#### [.NET Core-CLI](core/miscellaneous/cli/dotnet.md)
#### [DbContext-Instanzerstellung zur Entwurfszeit](core/miscellaneous/cli/dbcontext-creation.md)
#### [Entwurfszeitdienste](core/miscellaneous/cli/services.md)

### Verschiedenes
#### [Verbindungszeichenfolgen](core/miscellaneous/connection-strings.md)
#### [Logging (Protokollierung)](core/miscellaneous/logging.md)
#### [Verbindungsresilienz](core/miscellaneous/connection-resiliency.md)
#### [Testen](core/miscellaneous/testing/index.md)
##### [Testen mit SQLite](core/miscellaneous/testing/sqlite.md)
##### [Testen mit InMemory](core/miscellaneous/testing/in-memory.md)
#### [Konfigurieren einer DbContext-Instanz](core/miscellaneous/configuring-dbcontext.md)
#### [Durchführen eines Upgrades von 1.0 RC1 auf RC2](core/miscellaneous/rc1-rc2-upgrade.md)
#### [Durchführen eines Upgrades von 1.0 RC2 auf RTM](core/miscellaneous/rc2-rtm-upgrade.md)
#### [Durchführen eines Upgrades auf EF Core 2.0](core/miscellaneous/1x-2x-upgrade.md)

### [⤤ Referenz für die EF Core-API](https://docs.microsoft.com/dotnet/api/?view=efcore-2.1)

## [Entity Framework 6](ef6/index.md)

### [Neuigkeiten](ef6/what-is-new/index.md)
#### [Roadmap](ef6/what-is-new/roadmap.md)
#### [Frühere Releases](ef6/what-is-new/past-releases.md)
#### [Durchführen eines Upgrades auf EF6](ef6/what-is-new/upgrading-to-ef6.md)
#### [Visual Studio-Releases](ef6/what-is-new/visual-studio.md)

### [Erste Schritte](ef6/get-started.md)

### [Grundlagen](ef6/fundamentals/index.md)
#### [Verwenden von Entity Framework](ef6/fundamentals/install.md)
#### [Arbeiten mit DbContext](ef6/fundamentals/working-with-dbcontext.md)
#### [Grundlegendes zu Beziehungen](ef6/fundamentals/relationships.md)
#### [Asynchrone Abfrage und Speichern](ef6/fundamentals/async.md)
#### Konfiguration
##### [Codebasiert](ef6/fundamentals/configuring/code-based.md)
##### [Konfigurationsdatei](ef6/fundamentals/configuring/config-file.md)
##### [Verbindungszeichenfolgen](ef6/fundamentals/configuring/connection-strings.md)
##### [Abhängigkeitsauflösung](ef6/fundamentals/configuring/dependency-resolution.md)
#### [Verbindungsverwaltung](ef6/fundamentals/connection-management.md)
#### Verbindungsresilienz
##### [Wiederholungslogik](ef6/fundamentals/connection-resiliency/retry-logic.md)
##### [Fehler beim Transaktionscommit](ef6/fundamentals/connection-resiliency/commit-failures.md)
#### Datenbindung
##### [WinForms](ef6/fundamentals/databinding/winforms.md)
##### [WPF](ef6/fundamentals/databinding/wpf.md)
#### [Getrennte Entitäten](ef6/fundamentals/disconnected-entities/index.md)
##### [Selbst-protokollierende Entitäten](ef6/fundamentals/disconnected-entities/self-tracking-entities/index.md)
###### [Exemplarische Vorgehensweise](ef6/fundamentals/disconnected-entities/self-tracking-entities/walkthrough.md)
#### [Protokollierung und Abfangfunktion](ef6/fundamentals/logging-and-interception.md)
#### Leistung
##### [Überlegungen zur Leistung (Whitepaper)](ef6/fundamentals/performance/perf-whitepaper.md)
##### [Verwenden von NGen](ef6/fundamentals/performance/ngen.md)
##### [Verwenden vorab generierter Ansichten](ef6/fundamentals/performance/pre-generated-views.md)
#### [Anbieter](ef6/fundamentals/providers/index.md)
##### [EF6-Anbietermodell](ef6/fundamentals/providers/provider-model.md)
##### [Unterstützung für räumliche Daten in Anbietern](ef6/fundamentals/providers/spatial-support.md)
#### [Verwenden von Proxys](ef6/fundamentals/proxies.md)
#### Testen mit EF6
##### [Verwendung von Simulation](ef6/fundamentals/testing/mocking.md)
##### [Schreiben eigener Testdoubles](ef6/fundamentals/testing/writing-test-doubles.md)
##### [Testfähigkeit mit EF4 (Artikel)](ef6/fundamentals/testing/testability-article.md)

### [Erstellen eines Modells](ef6/modeling/index.md)
#### Verwendung von Code First
##### Workflows
###### [Mit einer neuen Datenbank](ef6/modeling/code-first/workflows/new-database.md)
###### [Mit einer vorhandenen Datenbank](ef6/modeling/code-first/workflows/existing-database.md)
##### [Datenanmerkungen](ef6/modeling/code-first/data-annotations.md)
##### [DbSets](ef6/modeling/code-first/dbsets.md)
##### Datentypen
###### [Enumerationen](ef6/modeling/code-first/data-types/enums.md)
###### [Spatial](ef6/modeling/code-first/data-types/spatial.md)
##### Konventionen
###### [Integrierte Konventionen](ef6/modeling/code-first/conventions/built-in.md)
###### [Benutzerdefinierte Konventionen](ef6/modeling/code-first/conventions/custom.md)
###### [Modellkonventionen](ef6/modeling/code-first/conventions/model.md)
##### Fluent-Konfiguration
###### [Beziehungen](ef6/modeling/code-first/fluent/relationships.md)
###### [Typen und Eigenschaften](ef6/modeling/code-first/fluent/types-and-properties.md)
###### [Verwenden in Visual Basic](ef6/modeling/code-first/fluent/vb.md)
###### [Mapping der gespeicherten Prozedur](ef6/modeling/code-first/fluent/cud-stored-procedures.md)
##### [Migrationen](ef6/modeling/code-first/migrations/index.md)
###### [Automatische Migrationen](ef6/modeling/code-first/migrations/automatic.md)
###### [Arbeiten mit vorhandenen Datenbanken](ef6/modeling/code-first/migrations/existing-database.md)
###### [Anpassen des Migrationsverlaufs](ef6/modeling/code-first/migrations/history-customization.md)
###### [Verwenden von migrate.exe](ef6/modeling/code-first/migrations/migrate-exe.md)
###### [Migration in Teamumgebungen](ef6/modeling/code-first/migrations/teams.md)

#### Verwendung des EF-Designers
##### Workflows
###### [Model First](ef6/modeling/designer/workflows/model-first.md)
###### [Database First](ef6/modeling/designer/workflows/database-first.md)
##### Datentypen
###### [Komplexe Typen](ef6/modeling/designer/data-types/complex-types.md)
###### [Enumerationen](ef6/modeling/designer/data-types/enums.md)
###### [Spatial](ef6/modeling/designer/data-types/spatial.md)
##### Aufteilung von Mappings
###### [Entitätsaufteilung](ef6/modeling/designer/entity-splitting.md)
###### [Tabellenaufteilung](ef6/modeling/designer/table-splitting.md)
##### Ver
###### [Tabelle pro Hierarchie](ef6/modeling/designer/inheritance/tph.md)
###### [Tabelle pro Typ](ef6/modeling/designer/inheritance/tpt.md)
##### Aufteilen gespeicherter Prozeduren
###### [Query](ef6/modeling/designer/stored-procedures/query.md)
###### [Update (Aktualisieren)](ef6/modeling/designer/stored-procedures/cud.md)
##### [Zuordnen von Beziehungen](ef6/modeling/designer/relationships.md)
##### [Mehrere Diagramme](ef6/modeling/designer/multiple-diagrams.md)
##### [Auswählen der Laufzeitversion](ef6/modeling/designer/select-runtime-version.md)
##### [Codegenerierung](ef6/modeling/designer/codegen/index.md)
###### [Älterer ObjectContext ](ef6/modeling/designer/codegen/legacy-objectcontext.md)
##### Erweitert
###### EDMX-Dateiformat
####### [CSDL-Spezifikation](ef6/modeling/designer/advanced/edmx/csdl-spec.md)
####### [MSL-Spezifikation](ef6/modeling/designer/advanced/edmx/msl-spec.md)
####### [SSDL-Spezifikation](ef6/modeling/designer/advanced/edmx/ssdl-spec.md)
###### [Definieren der Abfrage](ef6/modeling/designer/advanced/defining-query.md)
###### [Mehrere Resultsets](ef6/modeling/designer/advanced/multiple-result-sets.md)
###### [Tabellenwertfunktionen](ef6/modeling/designer/advanced/tvfs.md)
##### [Tastenkombinationen](ef6/modeling/designer/keyboard-shortcuts.md)

### [Abfragen von Daten](ef6/querying/index.md)
#### [Load-Methode](ef6/querying/load-method.md)
#### [Lokale Daten](ef6/querying/local-data.md)
#### [Abfragen mit Nachverfolgung und ohne Nachverfolgung](ef6/querying/no-tracking.md)
#### [Verwendung unformatierter SQL-Abfragen](ef6/querying/raw-sql.md)
#### [Abfragen dazugehöriger Daten](ef6/querying/related-data.md)

### [Speichern von Daten](ef6/saving/index.md)
#### Änderungsnachverfolgung
##### [Änderung an der automatischen Erkennung](ef6/saving/change-tracking/auto-detect-changes.md)
##### [Entitätszustand](ef6/saving/change-tracking/entity-state.md)
##### [Eigenschaftswerte](ef6/saving/change-tracking/property-values.md)
#### [Behandeln von Nebenläufigkeitskonflikt](ef6/saving/concurrency.md)
#### [Verwenden von Transaktionen](ef6/saving/transactions.md)
#### [Datenvalidierung](ef6/saving/validation.md)

### [Additional Resources](ef6/resources/index.md) (Zusätzliche MSBuild-Ressourcen)
#### [Blogs](ef6/resources/blogs.md)
#### [Fallstudien](ef6/resources/case-studies.md)
#### [Mitwirken](ef6/resources/contribute.md)
#### [Anzeigen der Hilfe](ef6/resources/get-help.md)
#### [Glossar](ef6/resources/glossary.md)
#### [Die Beispieldatenbank „School“](ef6/resources/school-database.md)
#### [Tools und Erweiterungen](ef6/resources/tools.md)
#### Lizenzen
##### EF5
###### [Chinesisch (vereinfacht)](ef6/resources/licenses/ef5/chs.md)
###### [Chinesisch (traditionell)](ef6/resources/licenses/ef5/cht.md)
###### [Deutsch](ef6/resources/licenses/ef5/deu.md)
###### [Englisch](ef6/resources/licenses/ef5/enu.md)
###### [Spanisch](ef6/resources/licenses/ef5/esn.md)
###### [Französisch](ef6/resources/licenses/ef5/fra.md)
###### [Italienisch](ef6/resources/licenses/ef5/ita.md)
###### [Japanisch](ef6/resources/licenses/ef5/jpn.md)
###### [Koreanisch](ef6/resources/licenses/ef5/kor.md)
###### [Russisch](ef6/resources/licenses/ef5/rus.md)
##### EF6
###### Vorabversion
####### [Alpha](ef6/resources/licenses/ef6/prerelease/alpha.md)
####### [Beta: Release Candidate](ef6/resources/licenses/ef6/prerelease/beta-rc.md)
###### [Chinesisch (vereinfacht)](ef6/resources/licenses/ef6/chs.md)
###### [Chinesisch (traditionell)](ef6/resources/licenses/ef6/cht.md)
###### [Deutsch](ef6/resources/licenses/ef6/deu.md)
###### [Englisch](ef6/resources/licenses/ef6/enu.md)
###### [Spanisch](ef6/resources/licenses/ef6/esn.md)
###### [Französisch](ef6/resources/licenses/ef6/fra.md)
###### [Italienisch](ef6/resources/licenses/ef6/ita.md)
###### [Japanisch](ef6/resources/licenses/ef6/jpn.md)
###### [Koreanisch](ef6/resources/licenses/ef6/kor.md)
###### [Russisch](ef6/resources/licenses/ef6/rus.md)

### [⤤ Referenz für die EF6-API](https://msdn.microsoft.com/library/dn223258.aspx)
