<span data-ttu-id="5bda1-101">**Warnung**: der folgende code verwendet `GetTempFileName`, wodurch eine `IOException` Wenn mehr als 65535 Dateien erstellt werden, ohne vorherige temporäre Dateien zu löschen.</span><span class="sxs-lookup"><span data-stu-id="5bda1-101">**Warning**: The following code uses `GetTempFileName`, which throws an `IOException` if more than 65535 files are created without deleting previous temporary files.</span></span> <span data-ttu-id="5bda1-102">Eine wirkliche app temporäre Dateien löschen oder verwenden sollten `GetTempPath` und `GetRandomFileName` temporären Dateinamen zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="5bda1-102">A real app should either delete temporary files or use `GetTempPath` and `GetRandomFileName` to create temporary file names.</span></span> <span data-ttu-id="5bda1-103">Der Grenzwert von 65535 Dateien ist pro Server, damit Sie alle 65535 Dateien auf dem Server eine andere app verwenden kann.</span><span class="sxs-lookup"><span data-stu-id="5bda1-103">The 65535 files limit is per server, so another app on the server can use up all 65535 files.</span></span> 