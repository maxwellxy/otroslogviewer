# Log parsers #

When you configure your application logging (log4j, JDK logging or other), you have to define log format/layout. OtrosLogViewer can read log files with standard patterns (XML, SimpleFormatter) or cutsom pattern definied by Log4j PatternLayout.

OtrosLogViewer is shipped with predifinied list of log parsers, but you can also create own parser using property file.It is possible to create log parser. See more in [Developing plugin guide](ImplementLogImporter.md)

Log file can be compressed by gzip.

