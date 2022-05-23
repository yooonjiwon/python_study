# Logging

Logging can be coded like below. This module provides log message tracking series of events.  
Loggign has five levels of message: **degub, info, warning, error, and critical.**

```python
import logging

logger = logging.get_Logger(__name__)

logger.debug("DEBUG") 
logger.info("INFO") 
logger.warn("WARNING")
logger.error("ERROR")
logger.critical("CRITICAL")
```
