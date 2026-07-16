# 📊 ANTA Report <a id="anta-report"></a>

**Table of Contents:**

- [ANTA Report](#anta-report)
  - [Test Results Summary](#test-results-summary)
    - [Summary Totals](#summary-totals)
    - [Summary Totals Device Under Test](#summary-totals-device-under-test)
    - [Summary Totals Per Category](#summary-totals-per-category)
  - [Test Results](#test-results)

## 📉 Test Results Summary <a id="test-results-summary"></a>

### 🔢 Summary Totals <a id="summary-totals"></a>

| Total Tests | ✅&nbsp;Success | ⏭️&nbsp;Skipped | ❌&nbsp;Failure | ❗&nbsp;Error |
| :- | :- | :- | :- | :- |
| 744 | 678 | 0 | 66 | 0 |

### 🔌 Summary Totals Device Under Test <a id="summary-totals-device-under-test"></a>

| Device | Total Tests | ✅&nbsp;Success | ⏭️&nbsp;Skipped | ❌&nbsp;Failure | ❗&nbsp;Error | Categories Skipped | Categories Failed |
| :- | :- | :- | :- | :- | :- | :- | :- |
| **c1-borderleaf1** | 26 | 24 | 0 | 2 | 0 | - | Logging, System |
| **c1-borderleaf2** | 26 | 24 | 0 | 2 | 0 | - | Logging, System |
| **c1-leaf1** | 26 | 24 | 0 | 2 | 0 | - | Logging, System |
| **c1-leaf2** | 26 | 24 | 0 | 2 | 0 | - | Logging, System |
| **c1-leaf3** | 26 | 24 | 0 | 2 | 0 | - | Logging, System |
| **c1-leaf4** | 26 | 24 | 0 | 2 | 0 | - | Logging, System |
| **c1-leaf5** | 26 | 24 | 0 | 2 | 0 | - | Logging, System |
| **c1-leaf6** | 26 | 22 | 0 | 4 | 0 | - | Interfaces, Logging, System |
| **c1-spine1** | 20 | 18 | 0 | 2 | 0 | - | Logging, System |
| **c1-spine2** | 20 | 18 | 0 | 2 | 0 | - | Logging, System |
| **c2-borderleaf1** | 26 | 24 | 0 | 2 | 0 | - | Logging, System |
| **c2-borderleaf2** | 26 | 24 | 0 | 2 | 0 | - | Logging, System |
| **c2-leaf1** | 26 | 24 | 0 | 2 | 0 | - | Logging, System |
| **c2-leaf2** | 26 | 24 | 0 | 2 | 0 | - | Logging, System |
| **c2-leaf3** | 26 | 24 | 0 | 2 | 0 | - | Logging, System |
| **c2-leaf4** | 26 | 24 | 0 | 2 | 0 | - | Logging, System |
| **c2-leaf5** | 26 | 24 | 0 | 2 | 0 | - | Logging, System |
| **c2-leaf6** | 26 | 22 | 0 | 4 | 0 | - | Interfaces, Logging, System |
| **c2-spine1** | 20 | 18 | 0 | 2 | 0 | - | Logging, System |
| **c2-spine2** | 20 | 18 | 0 | 2 | 0 | - | Logging, System |
| **c3-borderleaf1** | 26 | 24 | 0 | 2 | 0 | - | Logging, System |
| **c3-borderleaf2** | 26 | 24 | 0 | 2 | 0 | - | Logging, System |
| **c3-leaf1** | 26 | 24 | 0 | 2 | 0 | - | Logging, System |
| **c3-leaf2** | 26 | 24 | 0 | 2 | 0 | - | Logging, System |
| **c3-leaf3** | 26 | 24 | 0 | 2 | 0 | - | Logging, System |
| **c3-leaf4** | 26 | 24 | 0 | 2 | 0 | - | Logging, System |
| **c3-leaf5** | 26 | 24 | 0 | 2 | 0 | - | Logging, System |
| **c3-leaf6** | 26 | 22 | 0 | 4 | 0 | - | Interfaces, Logging, System |
| **c3-spine1** | 20 | 18 | 0 | 2 | 0 | - | Logging, System |
| **c3-spine2** | 20 | 18 | 0 | 2 | 0 | - | Logging, System |

### 🗂️ Summary Totals Per Category <a id="summary-totals-per-category"></a>

| Test Category | Total Tests | ✅&nbsp;Success | ⏭️&nbsp;Skipped | ❌&nbsp;Failure | ❗&nbsp;Error |
| :- | :- | :- | :- | :- | :- |
| **BGP** | 30 | 30 | 0 | 0 | 0 |
| **Configuration** | 60 | 60 | 0 | 0 | 0 |
| **Connectivity** | 60 | 60 | 0 | 0 | 0 |
| **Interfaces** | 198 | 192 | 0 | 6 | 0 |
| **Logging** | 30 | 0 | 0 | 30 | 0 |
| **MLAG** | 72 | 72 | 0 | 0 | 0 |
| **Routing** | 30 | 30 | 0 | 0 | 0 |
| **STP** | 30 | 30 | 0 | 0 | 0 |
| **System** | 210 | 180 | 0 | 30 | 0 |
| **VXLAN** | 24 | 24 | 0 | 0 | 0 |

## 🧪 Test Results <a id="test-results"></a>

| Device | Categories | Test | Description | Result | Messages |
| :- | :- | :- | :- | :- | :- |
| c1-borderleaf1 | Logging | VerifyLoggingErrors | Verifies there are no syslog messages with a severity of ERRORS or higher. | ❌&nbsp;Failure | Device has reported syslog messages with a severity of ERRORS or higher:<br>Jul 16 00:22:28 c1-borderleaf1 ProcMgr: %PROCMGR-3-SHUTDOWNREQUESTED: ProcMgr shutdown requested via SIGQUIT or SIGTERM to worker (PID=1793) -- Master ProcMgr (PID=1793) exiting.<br> Jul 16 00:22:28 c1-borderleaf1 StpTxRx: %FWK-3-SOCKET_CLOSE_REMOTE: Connection to Stp (pid:3348) at tbl://stpListen/+n closed by peer (EOF)<br> Jul 16 00:22:28 c1-borderleaf1 StpTxRx: %FWK-3-MOUNT_PEER_CLOSED: Peer closed socket connection. (tbl://stpListen/+n-in)(Stp (pid:3348))<br> <br> |
| c1-borderleaf1 | System | VerifyNTP | Verifies if NTP is synchronised. | ❌&nbsp;Failure | NTP status mismatch - Expected: synchronised Actual: NTP is disabled. |
| c1-borderleaf2 | Logging | VerifyLoggingErrors | Verifies there are no syslog messages with a severity of ERRORS or higher. | ❌&nbsp;Failure | Device has reported syslog messages with a severity of ERRORS or higher:<br>Jul 16 00:22:22 c1-borderleaf2 ProcMgr: %PROCMGR-3-SHUTDOWNREQUESTED: ProcMgr shutdown requested via SIGQUIT or SIGTERM to worker (PID=1790) -- Master ProcMgr (PID=1790) exiting.<br> <br> |
| c1-borderleaf2 | System | VerifyNTP | Verifies if NTP is synchronised. | ❌&nbsp;Failure | NTP status mismatch - Expected: synchronised Actual: NTP is disabled. |
| c1-leaf1 | Logging | VerifyLoggingErrors | Verifies there are no syslog messages with a severity of ERRORS or higher. | ❌&nbsp;Failure | Device has reported syslog messages with a severity of ERRORS or higher:<br>Jul 16 00:22:24 c1-leaf1 ProcMgr: %PROCMGR-3-SHUTDOWNREQUESTED: ProcMgr shutdown requested via SIGQUIT or SIGTERM to worker (PID=1803) -- Master ProcMgr (PID=1803) exiting.<br> Jul 16 00:22:24 c1-leaf1 StpTxRx: %FWK-3-SOCKET_CLOSE_REMOTE: Connection to Stp (pid:3316) at tbl://stpListen/+n closed by peer (EOF)<br> Jul 16 00:22:24 c1-leaf1 StpTxRx: %FWK-3-MOUNT_PEER_CLOSED: Peer closed socket connection. (tbl://stpListen/+n-in)(Stp (pid:3316))<br> <br> |
| c1-leaf1 | System | VerifyNTP | Verifies if NTP is synchronised. | ❌&nbsp;Failure | NTP status mismatch - Expected: synchronised Actual: NTP is disabled. |
| c1-leaf2 | Logging | VerifyLoggingErrors | Verifies there are no syslog messages with a severity of ERRORS or higher. | ❌&nbsp;Failure | Device has reported syslog messages with a severity of ERRORS or higher:<br>Jul 16 00:22:27 c1-leaf2 ProcMgr: %PROCMGR-3-SHUTDOWNREQUESTED: ProcMgr shutdown requested via SIGQUIT or SIGTERM to worker (PID=1799) -- Master ProcMgr (PID=1799) exiting.<br> <br> |
| c1-leaf2 | System | VerifyNTP | Verifies if NTP is synchronised. | ❌&nbsp;Failure | NTP status mismatch - Expected: synchronised Actual: NTP is disabled. |
| c1-leaf3 | Logging | VerifyLoggingErrors | Verifies there are no syslog messages with a severity of ERRORS or higher. | ❌&nbsp;Failure | Device has reported syslog messages with a severity of ERRORS or higher:<br>Jul 16 00:22:30 c1-leaf3 ProcMgr: %PROCMGR-3-SHUTDOWNREQUESTED: ProcMgr shutdown requested via SIGQUIT or SIGTERM to worker (PID=1803) -- Master ProcMgr (PID=1803) exiting.<br> Jul 16 00:22:30 c1-leaf3 StpTxRx: %FWK-3-SOCKET_CLOSE_REMOTE: Connection to Stp (pid:3291) at tbl://stpListen/+n closed by peer (EOF)<br> Jul 16 00:22:30 c1-leaf3 StpTxRx: %FWK-3-MOUNT_PEER_CLOSED: Peer closed socket connection. (tbl://stpListen/+n-in)(Stp (pid:3291))<br> <br> |
| c1-leaf3 | System | VerifyNTP | Verifies if NTP is synchronised. | ❌&nbsp;Failure | NTP status mismatch - Expected: synchronised Actual: NTP is disabled. |
| c1-leaf4 | Logging | VerifyLoggingErrors | Verifies there are no syslog messages with a severity of ERRORS or higher. | ❌&nbsp;Failure | Device has reported syslog messages with a severity of ERRORS or higher:<br>Jul 16 00:22:28 c1-leaf4 ProcMgr: %PROCMGR-3-SHUTDOWNREQUESTED: ProcMgr shutdown requested via SIGQUIT or SIGTERM to worker (PID=1803) -- Master ProcMgr (PID=1803) exiting.<br> <br> |
| c1-leaf4 | System | VerifyNTP | Verifies if NTP is synchronised. | ❌&nbsp;Failure | NTP status mismatch - Expected: synchronised Actual: NTP is disabled. |
| c1-leaf5 | Logging | VerifyLoggingErrors | Verifies there are no syslog messages with a severity of ERRORS or higher. | ❌&nbsp;Failure | Device has reported syslog messages with a severity of ERRORS or higher:<br>Jul 16 00:22:28 c1-leaf5 ProcMgr: %PROCMGR-3-SHUTDOWNREQUESTED: ProcMgr shutdown requested via SIGQUIT or SIGTERM to worker (PID=1800) -- Master ProcMgr (PID=1800) exiting.<br> <br> |
| c1-leaf5 | System | VerifyNTP | Verifies if NTP is synchronised. | ❌&nbsp;Failure | NTP status mismatch - Expected: synchronised Actual: NTP is disabled. |
| c1-leaf6 | Interfaces | VerifyInterfacesStatus | Verifies the operational states of specified interfaces to ensure they match expected configurations. | ❌&nbsp;Failure | Interface: Port-Channel10 - Status mismatch - Expected: up/up, Actual: down/lowerLayerDown |
| c1-leaf6 | Interfaces | VerifyPortChannels | Verifies there are no inactive ports in port channels. | ❌&nbsp;Failure | Interface: Port-Channel10 - Inactive port(s) - Ethernet10 |
| c1-leaf6 | Logging | VerifyLoggingErrors | Verifies there are no syslog messages with a severity of ERRORS or higher. | ❌&nbsp;Failure | Device has reported syslog messages with a severity of ERRORS or higher:<br>Jul 16 00:22:32 c1-leaf6 ProcMgr: %PROCMGR-3-SHUTDOWNREQUESTED: ProcMgr shutdown requested via SIGQUIT or SIGTERM to worker (PID=1805) -- Master ProcMgr (PID=1805) exiting.<br> Jul 16 00:22:32 c1-leaf6 StpTxRx: %FWK-3-SOCKET_CLOSE_REMOTE: Connection to Stp (pid:3349) at tbl://stpListen/+n closed by peer (EOF)<br> Jul 16 00:22:32 c1-leaf6 StpTxRx: %FWK-3-MOUNT_PEER_CLOSED: Peer closed socket connection. (tbl://stpListen/+n-in)(Stp (pid:3349))<br> <br> |
| c1-leaf6 | System | VerifyNTP | Verifies if NTP is synchronised. | ❌&nbsp;Failure | NTP status mismatch - Expected: synchronised Actual: NTP is disabled. |
| c1-spine1 | Logging | VerifyLoggingErrors | Verifies there are no syslog messages with a severity of ERRORS or higher. | ❌&nbsp;Failure | Device has reported syslog messages with a severity of ERRORS or higher:<br>Jul 16 00:22:31 c1-spine1 ProcMgr: %PROCMGR-3-SHUTDOWNREQUESTED: ProcMgr shutdown requested via SIGQUIT or SIGTERM to worker (PID=1805) -- Master ProcMgr (PID=1805) exiting.<br> <br> |
| c1-spine1 | System | VerifyNTP | Verifies if NTP is synchronised. | ❌&nbsp;Failure | NTP status mismatch - Expected: synchronised Actual: NTP is disabled. |
| c1-spine2 | Logging | VerifyLoggingErrors | Verifies there are no syslog messages with a severity of ERRORS or higher. | ❌&nbsp;Failure | Device has reported syslog messages with a severity of ERRORS or higher:<br>Jul 16 00:22:36 c1-spine2 ProcMgr: %PROCMGR-3-SHUTDOWNREQUESTED: ProcMgr shutdown requested via SIGQUIT or SIGTERM to worker (PID=1807) -- Master ProcMgr (PID=1807) exiting.<br> Jul 16 00:22:36 c1-spine2 StpTxRx: %FWK-3-SOCKET_CLOSE_REMOTE: Connection to Stp (pid:3269) at tbl://stpListen/+n closed by peer (EOF)<br> Jul 16 00:22:36 c1-spine2 StpTxRx: %FWK-3-MOUNT_PEER_CLOSED: Peer closed socket connection. (tbl://stpListen/+n-in)(Stp (pid:3269))<br> <br> |
| c1-spine2 | System | VerifyNTP | Verifies if NTP is synchronised. | ❌&nbsp;Failure | NTP status mismatch - Expected: synchronised Actual: NTP is disabled. |
| c2-borderleaf1 | Logging | VerifyLoggingErrors | Verifies there are no syslog messages with a severity of ERRORS or higher. | ❌&nbsp;Failure | Device has reported syslog messages with a severity of ERRORS or higher:<br>Jul 16 00:22:33 c2-borderleaf1 ProcMgr: %PROCMGR-3-SHUTDOWNREQUESTED: ProcMgr shutdown requested via SIGQUIT or SIGTERM to worker (PID=1796) -- Master ProcMgr (PID=1796) exiting.<br> Jul 16 00:22:33 c2-borderleaf1 StpTxRx: %FWK-3-SOCKET_CLOSE_REMOTE: Connection to Stp (pid:3304) at tbl://stpListen/+n closed by peer (EOF)<br> Jul 16 00:22:33 c2-borderleaf1 StpTxRx: %FWK-3-MOUNT_PEER_CLOSED: Peer closed socket connection. (tbl://stpListen/+n-in)(Stp (pid:3304))<br> <br> |
| c2-borderleaf1 | System | VerifyNTP | Verifies if NTP is synchronised. | ❌&nbsp;Failure | NTP status mismatch - Expected: synchronised Actual: NTP is disabled. |
| c2-borderleaf2 | Logging | VerifyLoggingErrors | Verifies there are no syslog messages with a severity of ERRORS or higher. | ❌&nbsp;Failure | Device has reported syslog messages with a severity of ERRORS or higher:<br>Jul 16 00:22:35 c2-borderleaf2 ProcMgr: %PROCMGR-3-SHUTDOWNREQUESTED: ProcMgr shutdown requested via SIGQUIT or SIGTERM to worker (PID=1795) -- Master ProcMgr (PID=1795) exiting.<br> Jul 16 00:22:35 c2-borderleaf2 StpTxRx: %FWK-3-SOCKET_CLOSE_REMOTE: Connection to Stp (pid:3323) at tbl://stpListen/+n closed by peer (EOF)<br> Jul 16 00:22:35 c2-borderleaf2 StpTxRx: %FWK-3-MOUNT_PEER_CLOSED: Peer closed socket connection. (tbl://stpListen/+n-in)(Stp (pid:3323))<br> <br> |
| c2-borderleaf2 | System | VerifyNTP | Verifies if NTP is synchronised. | ❌&nbsp;Failure | NTP status mismatch - Expected: synchronised Actual: NTP is disabled. |
| c2-leaf1 | Logging | VerifyLoggingErrors | Verifies there are no syslog messages with a severity of ERRORS or higher. | ❌&nbsp;Failure | Device has reported syslog messages with a severity of ERRORS or higher:<br>Jul 16 00:22:35 c2-leaf1 ProcMgr: %PROCMGR-3-SHUTDOWNREQUESTED: ProcMgr shutdown requested via SIGQUIT or SIGTERM to worker (PID=1806) -- Master ProcMgr (PID=1806) exiting.<br> <br> |
| c2-leaf1 | System | VerifyNTP | Verifies if NTP is synchronised. | ❌&nbsp;Failure | NTP status mismatch - Expected: synchronised Actual: NTP is disabled. |
| c2-leaf2 | Logging | VerifyLoggingErrors | Verifies there are no syslog messages with a severity of ERRORS or higher. | ❌&nbsp;Failure | Device has reported syslog messages with a severity of ERRORS or higher:<br>Jul 16 00:22:36 c2-leaf2 ProcMgr: %PROCMGR-3-SHUTDOWNREQUESTED: ProcMgr shutdown requested via SIGQUIT or SIGTERM to worker (PID=1800) -- Master ProcMgr (PID=1800) exiting.<br> Jul 16 00:22:37 c2-leaf2 Stp: %FWK-3-SOCKET_CLOSE_REMOTE: Connection to StpTxRx (pid:3317) at tbl://stpTxRxListen/+n closed by peer (EOF)<br> Jul 16 00:22:37 c2-leaf2 Stp: %FWK-3-MOUNT_PEER_CLOSED: Peer closed socket connection. (tbl://stpTxRxListen/+n-in)(StpTxRx (pid:3317))<br> <br> |
| c2-leaf2 | System | VerifyNTP | Verifies if NTP is synchronised. | ❌&nbsp;Failure | NTP status mismatch - Expected: synchronised Actual: NTP is disabled. |
| c2-leaf3 | Logging | VerifyLoggingErrors | Verifies there are no syslog messages with a severity of ERRORS or higher. | ❌&nbsp;Failure | Device has reported syslog messages with a severity of ERRORS or higher:<br>Jul 16 00:22:37 c2-leaf3 ProcMgr: %PROCMGR-3-SHUTDOWNREQUESTED: ProcMgr shutdown requested via SIGQUIT or SIGTERM to worker (PID=1806) -- Master ProcMgr (PID=1806) exiting.<br> Jul 16 00:22:37 c2-leaf3 StpTxRx: %FWK-3-SOCKET_CLOSE_REMOTE: Connection to Stp (pid:3335) at tbl://stpListen/+n closed by peer (EOF)<br> Jul 16 00:22:37 c2-leaf3 StpTxRx: %FWK-3-MOUNT_PEER_CLOSED: Peer closed socket connection. (tbl://stpListen/+n-in)(Stp (pid:3335))<br> Jul 16 05:56:04 c2-leaf3 Bgp: %BGP-3-NOTIFICATION: sent to neighbor 10.255.20.121 (VRF default AS 65010) 6/7 (Cease/connection collision resolution) 0 bytes <br> <br> |
| c2-leaf3 | System | VerifyNTP | Verifies if NTP is synchronised. | ❌&nbsp;Failure | NTP status mismatch - Expected: synchronised Actual: NTP is disabled. |
| c2-leaf4 | Logging | VerifyLoggingErrors | Verifies there are no syslog messages with a severity of ERRORS or higher. | ❌&nbsp;Failure | Device has reported syslog messages with a severity of ERRORS or higher:<br>Jul 16 00:22:41 c2-leaf4 ProcMgr: %PROCMGR-3-SHUTDOWNREQUESTED: ProcMgr shutdown requested via SIGQUIT or SIGTERM to worker (PID=1800) -- Master ProcMgr (PID=1800) exiting.<br> Jul 16 00:22:41 c2-leaf4 StpTxRx: %FWK-3-SOCKET_CLOSE_REMOTE: Connection to Stp (pid:3302) at tbl://stpListen/+n closed by peer (EOF)<br> Jul 16 00:22:41 c2-leaf4 StpTxRx: %FWK-3-MOUNT_PEER_CLOSED: Peer closed socket connection. (tbl://stpListen/+n-in)(Stp (pid:3302))<br> <br> |
| c2-leaf4 | System | VerifyNTP | Verifies if NTP is synchronised. | ❌&nbsp;Failure | NTP status mismatch - Expected: synchronised Actual: NTP is disabled. |
| c2-leaf5 | Logging | VerifyLoggingErrors | Verifies there are no syslog messages with a severity of ERRORS or higher. | ❌&nbsp;Failure | Device has reported syslog messages with a severity of ERRORS or higher:<br>Jul 16 00:22:36 c2-leaf5 ProcMgr: %PROCMGR-3-SHUTDOWNREQUESTED: ProcMgr shutdown requested via SIGQUIT or SIGTERM to worker (PID=1803) -- Master ProcMgr (PID=1803) exiting.<br> Jul 16 00:22:36 c2-leaf5 Stp: %FWK-3-SOCKET_CLOSE_REMOTE: Connection to StpTxRx (pid:3308) at tbl://stpTxRxListen/+n closed by peer (EOF)<br> Jul 16 00:22:36 c2-leaf5 Stp: %FWK-3-MOUNT_PEER_CLOSED: Peer closed socket connection. (tbl://stpTxRxListen/+n-in)(StpTxRx (pid:3308))<br> <br> |
| c2-leaf5 | System | VerifyNTP | Verifies if NTP is synchronised. | ❌&nbsp;Failure | NTP status mismatch - Expected: synchronised Actual: NTP is disabled. |
| c2-leaf6 | Interfaces | VerifyInterfacesStatus | Verifies the operational states of specified interfaces to ensure they match expected configurations. | ❌&nbsp;Failure | Interface: Port-Channel10 - Status mismatch - Expected: up/up, Actual: down/lowerLayerDown |
| c2-leaf6 | Interfaces | VerifyPortChannels | Verifies there are no inactive ports in port channels. | ❌&nbsp;Failure | Interface: Port-Channel10 - Inactive port(s) - Ethernet10 |
| c2-leaf6 | Logging | VerifyLoggingErrors | Verifies there are no syslog messages with a severity of ERRORS or higher. | ❌&nbsp;Failure | Device has reported syslog messages with a severity of ERRORS or higher:<br>Jul 16 00:22:36 c2-leaf6 ProcMgr: %PROCMGR-3-SHUTDOWNREQUESTED: ProcMgr shutdown requested via SIGQUIT or SIGTERM to worker (PID=1805) -- Master ProcMgr (PID=1805) exiting.<br> Jul 16 00:22:36 c2-leaf6 StpTxRx: %FWK-3-SOCKET_CLOSE_REMOTE: Connection to Stp (pid:3325) at tbl://stpListen/+n closed by peer (EOF)<br> Jul 16 00:22:36 c2-leaf6 StpTxRx: %FWK-3-MOUNT_PEER_CLOSED: Peer closed socket connection. (tbl://stpListen/+n-in)(Stp (pid:3325))<br> <br> |
| c2-leaf6 | System | VerifyNTP | Verifies if NTP is synchronised. | ❌&nbsp;Failure | NTP status mismatch - Expected: synchronised Actual: NTP is disabled. |
| c2-spine1 | Logging | VerifyLoggingErrors | Verifies there are no syslog messages with a severity of ERRORS or higher. | ❌&nbsp;Failure | Device has reported syslog messages with a severity of ERRORS or higher:<br>Jul 16 00:22:39 c2-spine1 ProcMgr: %PROCMGR-3-SHUTDOWNREQUESTED: ProcMgr shutdown requested via SIGQUIT or SIGTERM to worker (PID=1806) -- Master ProcMgr (PID=1806) exiting.<br> Jul 16 00:22:39 c2-spine1 Stp: %FWK-3-SOCKET_CLOSE_REMOTE: Connection to StpTxRx (pid:3280) at tbl://stpTxRxListen/+n closed by peer (EOF)<br> Jul 16 00:22:39 c2-spine1 Stp: %FWK-3-MOUNT_PEER_CLOSED: Peer closed socket connection. (tbl://stpTxRxListen/+n-in)(StpTxRx (pid:3280))<br> <br> |
| c2-spine1 | System | VerifyNTP | Verifies if NTP is synchronised. | ❌&nbsp;Failure | NTP status mismatch - Expected: synchronised Actual: NTP is disabled. |
| c2-spine2 | Logging | VerifyLoggingErrors | Verifies there are no syslog messages with a severity of ERRORS or higher. | ❌&nbsp;Failure | Device has reported syslog messages with a severity of ERRORS or higher:<br>Jul 16 00:22:39 c2-spine2 ProcMgr: %PROCMGR-3-SHUTDOWNREQUESTED: ProcMgr shutdown requested via SIGQUIT or SIGTERM to worker (PID=1805) -- Master ProcMgr (PID=1805) exiting.<br> Jul 16 00:22:39 c2-spine2 StpTxRx: %FWK-3-SOCKET_CLOSE_REMOTE: Connection to Stp (pid:3264) at tbl://stpListen/+n closed by peer (EOF)<br> Jul 16 05:56:05 c2-spine2 Bgp: %BGP-3-NOTIFICATION: sent to neighbor 10.255.20.124 (VRF default AS 65223) 6/7 (Cease/connection collision resolution) 0 bytes <br> <br> |
| c2-spine2 | System | VerifyNTP | Verifies if NTP is synchronised. | ❌&nbsp;Failure | NTP status mismatch - Expected: synchronised Actual: NTP is disabled. |
| c3-borderleaf1 | Logging | VerifyLoggingErrors | Verifies there are no syslog messages with a severity of ERRORS or higher. | ❌&nbsp;Failure | Device has reported syslog messages with a severity of ERRORS or higher:<br>Jul 16 00:22:43 c3-borderleaf1 ProcMgr: %PROCMGR-3-SHUTDOWNREQUESTED: ProcMgr shutdown requested via SIGQUIT or SIGTERM to worker (PID=1793) -- Master ProcMgr (PID=1793) exiting.<br> Jul 16 00:22:43 c3-borderleaf1 StpTxRx: %FWK-3-SOCKET_CLOSE_REMOTE: Connection to Stp (pid:3262) at tbl://stpListen/+n closed by peer (EOF)<br> Jul 16 00:22:43 c3-borderleaf1 StpTxRx: %FWK-3-MOUNT_PEER_CLOSED: Peer closed socket connection. (tbl://stpListen/+n-in)(Stp (pid:3262))<br> <br> |
| c3-borderleaf1 | System | VerifyNTP | Verifies if NTP is synchronised. | ❌&nbsp;Failure | NTP status mismatch - Expected: synchronised Actual: NTP is disabled. |
| c3-borderleaf2 | Logging | VerifyLoggingErrors | Verifies there are no syslog messages with a severity of ERRORS or higher. | ❌&nbsp;Failure | Device has reported syslog messages with a severity of ERRORS or higher:<br>Jul 16 00:22:43 c3-borderleaf2 ProcMgr: %PROCMGR-3-SHUTDOWNREQUESTED: ProcMgr shutdown requested via SIGQUIT or SIGTERM to worker (PID=1795) -- Master ProcMgr (PID=1795) exiting.<br> <br> |
| c3-borderleaf2 | System | VerifyNTP | Verifies if NTP is synchronised. | ❌&nbsp;Failure | NTP status mismatch - Expected: synchronised Actual: NTP is disabled. |
| c3-leaf1 | Logging | VerifyLoggingErrors | Verifies there are no syslog messages with a severity of ERRORS or higher. | ❌&nbsp;Failure | Device has reported syslog messages with a severity of ERRORS or higher:<br>Jul 16 00:22:41 c3-leaf1 ProcMgr: %PROCMGR-3-SHUTDOWNREQUESTED: ProcMgr shutdown requested via SIGQUIT or SIGTERM to worker (PID=1797) -- Master ProcMgr (PID=1797) exiting.<br> <br> |
| c3-leaf1 | System | VerifyNTP | Verifies if NTP is synchronised. | ❌&nbsp;Failure | NTP status mismatch - Expected: synchronised Actual: NTP is disabled. |
| c3-leaf2 | Logging | VerifyLoggingErrors | Verifies there are no syslog messages with a severity of ERRORS or higher. | ❌&nbsp;Failure | Device has reported syslog messages with a severity of ERRORS or higher:<br>Jul 16 00:22:40 c3-leaf2 ProcMgr: %PROCMGR-3-SHUTDOWNREQUESTED: ProcMgr shutdown requested via SIGQUIT or SIGTERM to worker (PID=1799) -- Master ProcMgr (PID=1799) exiting.<br> <br> |
| c3-leaf2 | System | VerifyNTP | Verifies if NTP is synchronised. | ❌&nbsp;Failure | NTP status mismatch - Expected: synchronised Actual: NTP is disabled. |
| c3-leaf3 | Logging | VerifyLoggingErrors | Verifies there are no syslog messages with a severity of ERRORS or higher. | ❌&nbsp;Failure | Device has reported syslog messages with a severity of ERRORS or higher:<br>Jul 16 00:22:45 c3-leaf3 ProcMgr: %PROCMGR-3-SHUTDOWNREQUESTED: ProcMgr shutdown requested via SIGQUIT or SIGTERM to worker (PID=1802) -- Master ProcMgr (PID=1802) exiting.<br> Jul 16 00:22:45 c3-leaf3 StpTxRx: %FWK-3-SOCKET_CLOSE_REMOTE: Connection to Stp (pid:3327) at tbl://stpListen/+n closed by peer (EOF)<br> Jul 16 00:22:45 c3-leaf3 StpTxRx: %FWK-3-MOUNT_PEER_CLOSED: Peer closed socket connection. (tbl://stpListen/+n-in)(Stp (pid:3327))<br> <br> |
| c3-leaf3 | System | VerifyNTP | Verifies if NTP is synchronised. | ❌&nbsp;Failure | NTP status mismatch - Expected: synchronised Actual: NTP is disabled. |
| c3-leaf4 | Logging | VerifyLoggingErrors | Verifies there are no syslog messages with a severity of ERRORS or higher. | ❌&nbsp;Failure | Device has reported syslog messages with a severity of ERRORS or higher:<br>Jul 16 00:22:44 c3-leaf4 ProcMgr: %PROCMGR-3-SHUTDOWNREQUESTED: ProcMgr shutdown requested via SIGQUIT or SIGTERM to worker (PID=1806) -- Master ProcMgr (PID=1806) exiting.<br> Jul 16 06:08:08 c3-leaf4 Bgp: %BGP-3-NOTIFICATION: sent to neighbor 10.255.30.131 (VRF default AS 65030) 6/7 (Cease/connection collision resolution) 0 bytes <br> <br> |
| c3-leaf4 | System | VerifyNTP | Verifies if NTP is synchronised. | ❌&nbsp;Failure | NTP status mismatch - Expected: synchronised Actual: NTP is disabled. |
| c3-leaf5 | Logging | VerifyLoggingErrors | Verifies there are no syslog messages with a severity of ERRORS or higher. | ❌&nbsp;Failure | Device has reported syslog messages with a severity of ERRORS or higher:<br>Jul 16 00:22:44 c3-leaf5 ProcMgr: %PROCMGR-3-SHUTDOWNREQUESTED: ProcMgr shutdown requested via SIGQUIT or SIGTERM to worker (PID=1806) -- Master ProcMgr (PID=1806) exiting.<br> <br> |
| c3-leaf5 | System | VerifyNTP | Verifies if NTP is synchronised. | ❌&nbsp;Failure | NTP status mismatch - Expected: synchronised Actual: NTP is disabled. |
| c3-leaf6 | Interfaces | VerifyInterfacesStatus | Verifies the operational states of specified interfaces to ensure they match expected configurations. | ❌&nbsp;Failure | Interface: Port-Channel10 - Status mismatch - Expected: up/up, Actual: down/lowerLayerDown |
| c3-leaf6 | Interfaces | VerifyPortChannels | Verifies there are no inactive ports in port channels. | ❌&nbsp;Failure | Interface: Port-Channel10 - Inactive port(s) - Ethernet10 |
| c3-leaf6 | Logging | VerifyLoggingErrors | Verifies there are no syslog messages with a severity of ERRORS or higher. | ❌&nbsp;Failure | Device has reported syslog messages with a severity of ERRORS or higher:<br>Jul 16 00:22:45 c3-leaf6 ProcMgr: %PROCMGR-3-SHUTDOWNREQUESTED: ProcMgr shutdown requested via SIGQUIT or SIGTERM to worker (PID=1801) -- Master ProcMgr (PID=1801) exiting.<br> Jul 16 00:22:45 c3-leaf6 StpTxRx: %FWK-3-SOCKET_CLOSE_REMOTE: Connection to Stp (pid:3312) at tbl://stpListen/+n closed by peer (EOF)<br> Jul 16 00:22:45 c3-leaf6 StpTxRx: %FWK-3-MOUNT_PEER_CLOSED: Peer closed socket connection. (tbl://stpListen/+n-in)(Stp (pid:3312))<br> <br> |
| c3-leaf6 | System | VerifyNTP | Verifies if NTP is synchronised. | ❌&nbsp;Failure | NTP status mismatch - Expected: synchronised Actual: NTP is disabled. |
| c3-spine1 | Logging | VerifyLoggingErrors | Verifies there are no syslog messages with a severity of ERRORS or higher. | ❌&nbsp;Failure | Device has reported syslog messages with a severity of ERRORS or higher:<br>Jul 16 00:22:46 c3-spine1 ProcMgr: %PROCMGR-3-SHUTDOWNREQUESTED: ProcMgr shutdown requested via SIGQUIT or SIGTERM to worker (PID=1805) -- Master ProcMgr (PID=1805) exiting.<br> Jul 16 00:22:46 c3-spine1 StpTxRx: %FWK-3-SOCKET_CLOSE_REMOTE: Connection to Stp (pid:3286) at tbl://stpListen/+n closed by peer (EOF)<br> Jul 16 00:22:46 c3-spine1 StpTxRx: %FWK-3-MOUNT_PEER_CLOSED: Peer closed socket connection. (tbl://stpListen/+n-in)(Stp (pid:3286))<br> <br> |
| c3-spine1 | System | VerifyNTP | Verifies if NTP is synchronised. | ❌&nbsp;Failure | NTP status mismatch - Expected: synchronised Actual: NTP is disabled. |
| c3-spine2 | Logging | VerifyLoggingErrors | Verifies there are no syslog messages with a severity of ERRORS or higher. | ❌&nbsp;Failure | Device has reported syslog messages with a severity of ERRORS or higher:<br>Jul 16 00:22:44 c3-spine2 ProcMgr: %PROCMGR-3-SHUTDOWNREQUESTED: ProcMgr shutdown requested via SIGQUIT or SIGTERM to worker (PID=1808) -- Master ProcMgr (PID=1808) exiting.<br> Jul 16 00:22:44 c3-spine2 StpTxRx: %FWK-3-SOCKET_CLOSE_REMOTE: Connection to Stp (pid:3319) at tbl://stpListen/+n closed by peer (EOF)<br> Jul 16 00:22:44 c3-spine2 StpTxRx: %FWK-3-MOUNT_PEER_CLOSED: Peer closed socket connection. (tbl://stpListen/+n-in)(Stp (pid:3319))<br> Jul 16 06:08:08 c3-spine2 Bgp: %BGP-3-NOTIFICATION: sent to neighbor 10.255.30.135 (VRF default AS 65233) 6/7 (Cease/connection collision resolution) 0 bytes <br> <br> |
| c3-spine2 | System | VerifyNTP | Verifies if NTP is synchronised. | ❌&nbsp;Failure | NTP status mismatch - Expected: synchronised Actual: NTP is disabled. |
| c1-borderleaf1 | BGP | VerifyBGPPeerSession | Verifies the session state of BGP peers. | ✅&nbsp;Success | - |
| c1-borderleaf1 | Configuration | VerifyRunningConfigDiffs | Verifies there is no difference between the running-config and the startup-config. | ✅&nbsp;Success | - |
| c1-borderleaf1 | Configuration | VerifyZeroTouch | Verifies ZeroTouch is disabled. | ✅&nbsp;Success | - |
| c1-borderleaf1 | Connectivity | VerifyLLDPNeighbors | Verifies the connection status of the specified LLDP (Link Layer Discovery Protocol) neighbors. | ✅&nbsp;Success | - |
| c1-borderleaf1 | Connectivity | VerifyReachability | Verifies point-to-point reachability between Ethernet interfaces. | ✅&nbsp;Success | - |
| c1-borderleaf1 | Interfaces | VerifyIllegalLACP | Verifies there are no illegal LACP packets in port channels. | ✅&nbsp;Success | - |
| c1-borderleaf1 | Interfaces | VerifyInterfaceDiscards | Verifies that the interfaces packet discard counters are equal to zero. | ✅&nbsp;Success | - |
| c1-borderleaf1 | Interfaces | VerifyInterfaceErrDisabled | Verifies there are no interfaces in the errdisabled state. | ✅&nbsp;Success | - |
| c1-borderleaf1 | Interfaces | VerifyInterfaceErrors | Verifies that the interfaces error counters are equal to zero. | ✅&nbsp;Success | - |
| c1-borderleaf1 | Interfaces | VerifyInterfaceUtilization | Verifies that the utilization of interfaces is below a certain threshold. | ✅&nbsp;Success | - |
| c1-borderleaf1 | Interfaces | VerifyInterfacesStatus | Verifies the operational states of specified interfaces to ensure they match expected configurations. | ✅&nbsp;Success | - |
| c1-borderleaf1 | Interfaces | VerifyPortChannels | Verifies there are no inactive ports in port channels. | ✅&nbsp;Success | - |
| c1-borderleaf1 | MLAG | VerifyMlagConfigSanity | Verifies there are no MLAG config-sanity inconsistencies. | ✅&nbsp;Success | - |
| c1-borderleaf1 | MLAG | VerifyMlagInterfaces | Verifies there are no inactive or active-partial MLAG ports. | ✅&nbsp;Success | - |
| c1-borderleaf1 | MLAG | VerifyMlagStatus | Verifies the health status of the MLAG configuration. | ✅&nbsp;Success | - |
| c1-borderleaf1 | Routing | VerifyRoutingProtocolModel | Verifies the configured routing protocol model. | ✅&nbsp;Success | - |
| c1-borderleaf1 | STP | VerifySTPCounters | Verifies there is no errors in STP BPDU packets. | ✅&nbsp;Success | - |
| c1-borderleaf1 | System | VerifyAgentLogs | Verifies there are no agent crash reports. | ✅&nbsp;Success | - |
| c1-borderleaf1 | System | VerifyCoredump | Verifies there are no core dump files. | ✅&nbsp;Success | - |
| c1-borderleaf1 | System | VerifyFileSystemUtilization | Verifies that no partition is utilizing more than 75% of its disk space. | ✅&nbsp;Success | - |
| c1-borderleaf1 | System | VerifyMaintenance | Verifies that the device is not currently under or entering maintenance. | ✅&nbsp;Success | - |
| c1-borderleaf1 | System | VerifyMemoryUtilization | Verifies whether the memory utilization is below 75%. | ✅&nbsp;Success | - |
| c1-borderleaf1 | System | VerifyReloadCause | Verifies the last reload cause of the device. | ✅&nbsp;Success | - |
| c1-borderleaf1 | VXLAN | VerifyVxlanConfigSanity | Verifies there are no VXLAN config-sanity inconsistencies. | ✅&nbsp;Success | - |
| c1-borderleaf2 | BGP | VerifyBGPPeerSession | Verifies the session state of BGP peers. | ✅&nbsp;Success | - |
| c1-borderleaf2 | Configuration | VerifyRunningConfigDiffs | Verifies there is no difference between the running-config and the startup-config. | ✅&nbsp;Success | - |
| c1-borderleaf2 | Configuration | VerifyZeroTouch | Verifies ZeroTouch is disabled. | ✅&nbsp;Success | - |
| c1-borderleaf2 | Connectivity | VerifyLLDPNeighbors | Verifies the connection status of the specified LLDP (Link Layer Discovery Protocol) neighbors. | ✅&nbsp;Success | - |
| c1-borderleaf2 | Connectivity | VerifyReachability | Verifies point-to-point reachability between Ethernet interfaces. | ✅&nbsp;Success | - |
| c1-borderleaf2 | Interfaces | VerifyIllegalLACP | Verifies there are no illegal LACP packets in port channels. | ✅&nbsp;Success | - |
| c1-borderleaf2 | Interfaces | VerifyInterfaceDiscards | Verifies that the interfaces packet discard counters are equal to zero. | ✅&nbsp;Success | - |
| c1-borderleaf2 | Interfaces | VerifyInterfaceErrDisabled | Verifies there are no interfaces in the errdisabled state. | ✅&nbsp;Success | - |
| c1-borderleaf2 | Interfaces | VerifyInterfaceErrors | Verifies that the interfaces error counters are equal to zero. | ✅&nbsp;Success | - |
| c1-borderleaf2 | Interfaces | VerifyInterfaceUtilization | Verifies that the utilization of interfaces is below a certain threshold. | ✅&nbsp;Success | - |
| c1-borderleaf2 | Interfaces | VerifyInterfacesStatus | Verifies the operational states of specified interfaces to ensure they match expected configurations. | ✅&nbsp;Success | - |
| c1-borderleaf2 | Interfaces | VerifyPortChannels | Verifies there are no inactive ports in port channels. | ✅&nbsp;Success | - |
| c1-borderleaf2 | MLAG | VerifyMlagConfigSanity | Verifies there are no MLAG config-sanity inconsistencies. | ✅&nbsp;Success | - |
| c1-borderleaf2 | MLAG | VerifyMlagInterfaces | Verifies there are no inactive or active-partial MLAG ports. | ✅&nbsp;Success | - |
| c1-borderleaf2 | MLAG | VerifyMlagStatus | Verifies the health status of the MLAG configuration. | ✅&nbsp;Success | - |
| c1-borderleaf2 | Routing | VerifyRoutingProtocolModel | Verifies the configured routing protocol model. | ✅&nbsp;Success | - |
| c1-borderleaf2 | STP | VerifySTPCounters | Verifies there is no errors in STP BPDU packets. | ✅&nbsp;Success | - |
| c1-borderleaf2 | System | VerifyAgentLogs | Verifies there are no agent crash reports. | ✅&nbsp;Success | - |
| c1-borderleaf2 | System | VerifyCoredump | Verifies there are no core dump files. | ✅&nbsp;Success | - |
| c1-borderleaf2 | System | VerifyFileSystemUtilization | Verifies that no partition is utilizing more than 75% of its disk space. | ✅&nbsp;Success | - |
| c1-borderleaf2 | System | VerifyMaintenance | Verifies that the device is not currently under or entering maintenance. | ✅&nbsp;Success | - |
| c1-borderleaf2 | System | VerifyMemoryUtilization | Verifies whether the memory utilization is below 75%. | ✅&nbsp;Success | - |
| c1-borderleaf2 | System | VerifyReloadCause | Verifies the last reload cause of the device. | ✅&nbsp;Success | - |
| c1-borderleaf2 | VXLAN | VerifyVxlanConfigSanity | Verifies there are no VXLAN config-sanity inconsistencies. | ✅&nbsp;Success | - |
| c1-leaf1 | BGP | VerifyBGPPeerSession | Verifies the session state of BGP peers. | ✅&nbsp;Success | - |
| c1-leaf1 | Configuration | VerifyRunningConfigDiffs | Verifies there is no difference between the running-config and the startup-config. | ✅&nbsp;Success | - |
| c1-leaf1 | Configuration | VerifyZeroTouch | Verifies ZeroTouch is disabled. | ✅&nbsp;Success | - |
| c1-leaf1 | Connectivity | VerifyLLDPNeighbors | Verifies the connection status of the specified LLDP (Link Layer Discovery Protocol) neighbors. | ✅&nbsp;Success | - |
| c1-leaf1 | Connectivity | VerifyReachability | Verifies point-to-point reachability between Ethernet interfaces. | ✅&nbsp;Success | - |
| c1-leaf1 | Interfaces | VerifyIllegalLACP | Verifies there are no illegal LACP packets in port channels. | ✅&nbsp;Success | - |
| c1-leaf1 | Interfaces | VerifyInterfaceDiscards | Verifies that the interfaces packet discard counters are equal to zero. | ✅&nbsp;Success | - |
| c1-leaf1 | Interfaces | VerifyInterfaceErrDisabled | Verifies there are no interfaces in the errdisabled state. | ✅&nbsp;Success | - |
| c1-leaf1 | Interfaces | VerifyInterfaceErrors | Verifies that the interfaces error counters are equal to zero. | ✅&nbsp;Success | - |
| c1-leaf1 | Interfaces | VerifyInterfaceUtilization | Verifies that the utilization of interfaces is below a certain threshold. | ✅&nbsp;Success | - |
| c1-leaf1 | Interfaces | VerifyInterfacesStatus | Verifies the operational states of specified interfaces to ensure they match expected configurations. | ✅&nbsp;Success | - |
| c1-leaf1 | Interfaces | VerifyPortChannels | Verifies there are no inactive ports in port channels. | ✅&nbsp;Success | - |
| c1-leaf1 | MLAG | VerifyMlagConfigSanity | Verifies there are no MLAG config-sanity inconsistencies. | ✅&nbsp;Success | - |
| c1-leaf1 | MLAG | VerifyMlagInterfaces | Verifies there are no inactive or active-partial MLAG ports. | ✅&nbsp;Success | - |
| c1-leaf1 | MLAG | VerifyMlagStatus | Verifies the health status of the MLAG configuration. | ✅&nbsp;Success | - |
| c1-leaf1 | Routing | VerifyRoutingProtocolModel | Verifies the configured routing protocol model. | ✅&nbsp;Success | - |
| c1-leaf1 | STP | VerifySTPCounters | Verifies there is no errors in STP BPDU packets. | ✅&nbsp;Success | - |
| c1-leaf1 | System | VerifyAgentLogs | Verifies there are no agent crash reports. | ✅&nbsp;Success | - |
| c1-leaf1 | System | VerifyCoredump | Verifies there are no core dump files. | ✅&nbsp;Success | - |
| c1-leaf1 | System | VerifyFileSystemUtilization | Verifies that no partition is utilizing more than 75% of its disk space. | ✅&nbsp;Success | - |
| c1-leaf1 | System | VerifyMaintenance | Verifies that the device is not currently under or entering maintenance. | ✅&nbsp;Success | - |
| c1-leaf1 | System | VerifyMemoryUtilization | Verifies whether the memory utilization is below 75%. | ✅&nbsp;Success | - |
| c1-leaf1 | System | VerifyReloadCause | Verifies the last reload cause of the device. | ✅&nbsp;Success | - |
| c1-leaf1 | VXLAN | VerifyVxlanConfigSanity | Verifies there are no VXLAN config-sanity inconsistencies. | ✅&nbsp;Success | - |
| c1-leaf2 | BGP | VerifyBGPPeerSession | Verifies the session state of BGP peers. | ✅&nbsp;Success | - |
| c1-leaf2 | Configuration | VerifyRunningConfigDiffs | Verifies there is no difference between the running-config and the startup-config. | ✅&nbsp;Success | - |
| c1-leaf2 | Configuration | VerifyZeroTouch | Verifies ZeroTouch is disabled. | ✅&nbsp;Success | - |
| c1-leaf2 | Connectivity | VerifyLLDPNeighbors | Verifies the connection status of the specified LLDP (Link Layer Discovery Protocol) neighbors. | ✅&nbsp;Success | - |
| c1-leaf2 | Connectivity | VerifyReachability | Verifies point-to-point reachability between Ethernet interfaces. | ✅&nbsp;Success | - |
| c1-leaf2 | Interfaces | VerifyIllegalLACP | Verifies there are no illegal LACP packets in port channels. | ✅&nbsp;Success | - |
| c1-leaf2 | Interfaces | VerifyInterfaceDiscards | Verifies that the interfaces packet discard counters are equal to zero. | ✅&nbsp;Success | - |
| c1-leaf2 | Interfaces | VerifyInterfaceErrDisabled | Verifies there are no interfaces in the errdisabled state. | ✅&nbsp;Success | - |
| c1-leaf2 | Interfaces | VerifyInterfaceErrors | Verifies that the interfaces error counters are equal to zero. | ✅&nbsp;Success | - |
| c1-leaf2 | Interfaces | VerifyInterfaceUtilization | Verifies that the utilization of interfaces is below a certain threshold. | ✅&nbsp;Success | - |
| c1-leaf2 | Interfaces | VerifyInterfacesStatus | Verifies the operational states of specified interfaces to ensure they match expected configurations. | ✅&nbsp;Success | - |
| c1-leaf2 | Interfaces | VerifyPortChannels | Verifies there are no inactive ports in port channels. | ✅&nbsp;Success | - |
| c1-leaf2 | MLAG | VerifyMlagConfigSanity | Verifies there are no MLAG config-sanity inconsistencies. | ✅&nbsp;Success | - |
| c1-leaf2 | MLAG | VerifyMlagInterfaces | Verifies there are no inactive or active-partial MLAG ports. | ✅&nbsp;Success | - |
| c1-leaf2 | MLAG | VerifyMlagStatus | Verifies the health status of the MLAG configuration. | ✅&nbsp;Success | - |
| c1-leaf2 | Routing | VerifyRoutingProtocolModel | Verifies the configured routing protocol model. | ✅&nbsp;Success | - |
| c1-leaf2 | STP | VerifySTPCounters | Verifies there is no errors in STP BPDU packets. | ✅&nbsp;Success | - |
| c1-leaf2 | System | VerifyAgentLogs | Verifies there are no agent crash reports. | ✅&nbsp;Success | - |
| c1-leaf2 | System | VerifyCoredump | Verifies there are no core dump files. | ✅&nbsp;Success | - |
| c1-leaf2 | System | VerifyFileSystemUtilization | Verifies that no partition is utilizing more than 75% of its disk space. | ✅&nbsp;Success | - |
| c1-leaf2 | System | VerifyMaintenance | Verifies that the device is not currently under or entering maintenance. | ✅&nbsp;Success | - |
| c1-leaf2 | System | VerifyMemoryUtilization | Verifies whether the memory utilization is below 75%. | ✅&nbsp;Success | - |
| c1-leaf2 | System | VerifyReloadCause | Verifies the last reload cause of the device. | ✅&nbsp;Success | - |
| c1-leaf2 | VXLAN | VerifyVxlanConfigSanity | Verifies there are no VXLAN config-sanity inconsistencies. | ✅&nbsp;Success | - |
| c1-leaf3 | BGP | VerifyBGPPeerSession | Verifies the session state of BGP peers. | ✅&nbsp;Success | - |
| c1-leaf3 | Configuration | VerifyRunningConfigDiffs | Verifies there is no difference between the running-config and the startup-config. | ✅&nbsp;Success | - |
| c1-leaf3 | Configuration | VerifyZeroTouch | Verifies ZeroTouch is disabled. | ✅&nbsp;Success | - |
| c1-leaf3 | Connectivity | VerifyLLDPNeighbors | Verifies the connection status of the specified LLDP (Link Layer Discovery Protocol) neighbors. | ✅&nbsp;Success | - |
| c1-leaf3 | Connectivity | VerifyReachability | Verifies point-to-point reachability between Ethernet interfaces. | ✅&nbsp;Success | - |
| c1-leaf3 | Interfaces | VerifyIllegalLACP | Verifies there are no illegal LACP packets in port channels. | ✅&nbsp;Success | - |
| c1-leaf3 | Interfaces | VerifyInterfaceDiscards | Verifies that the interfaces packet discard counters are equal to zero. | ✅&nbsp;Success | - |
| c1-leaf3 | Interfaces | VerifyInterfaceErrDisabled | Verifies there are no interfaces in the errdisabled state. | ✅&nbsp;Success | - |
| c1-leaf3 | Interfaces | VerifyInterfaceErrors | Verifies that the interfaces error counters are equal to zero. | ✅&nbsp;Success | - |
| c1-leaf3 | Interfaces | VerifyInterfaceUtilization | Verifies that the utilization of interfaces is below a certain threshold. | ✅&nbsp;Success | - |
| c1-leaf3 | Interfaces | VerifyInterfacesStatus | Verifies the operational states of specified interfaces to ensure they match expected configurations. | ✅&nbsp;Success | - |
| c1-leaf3 | Interfaces | VerifyPortChannels | Verifies there are no inactive ports in port channels. | ✅&nbsp;Success | - |
| c1-leaf3 | MLAG | VerifyMlagConfigSanity | Verifies there are no MLAG config-sanity inconsistencies. | ✅&nbsp;Success | - |
| c1-leaf3 | MLAG | VerifyMlagInterfaces | Verifies there are no inactive or active-partial MLAG ports. | ✅&nbsp;Success | - |
| c1-leaf3 | MLAG | VerifyMlagStatus | Verifies the health status of the MLAG configuration. | ✅&nbsp;Success | - |
| c1-leaf3 | Routing | VerifyRoutingProtocolModel | Verifies the configured routing protocol model. | ✅&nbsp;Success | - |
| c1-leaf3 | STP | VerifySTPCounters | Verifies there is no errors in STP BPDU packets. | ✅&nbsp;Success | - |
| c1-leaf3 | System | VerifyAgentLogs | Verifies there are no agent crash reports. | ✅&nbsp;Success | - |
| c1-leaf3 | System | VerifyCoredump | Verifies there are no core dump files. | ✅&nbsp;Success | - |
| c1-leaf3 | System | VerifyFileSystemUtilization | Verifies that no partition is utilizing more than 75% of its disk space. | ✅&nbsp;Success | - |
| c1-leaf3 | System | VerifyMaintenance | Verifies that the device is not currently under or entering maintenance. | ✅&nbsp;Success | - |
| c1-leaf3 | System | VerifyMemoryUtilization | Verifies whether the memory utilization is below 75%. | ✅&nbsp;Success | - |
| c1-leaf3 | System | VerifyReloadCause | Verifies the last reload cause of the device. | ✅&nbsp;Success | - |
| c1-leaf3 | VXLAN | VerifyVxlanConfigSanity | Verifies there are no VXLAN config-sanity inconsistencies. | ✅&nbsp;Success | - |
| c1-leaf4 | BGP | VerifyBGPPeerSession | Verifies the session state of BGP peers. | ✅&nbsp;Success | - |
| c1-leaf4 | Configuration | VerifyRunningConfigDiffs | Verifies there is no difference between the running-config and the startup-config. | ✅&nbsp;Success | - |
| c1-leaf4 | Configuration | VerifyZeroTouch | Verifies ZeroTouch is disabled. | ✅&nbsp;Success | - |
| c1-leaf4 | Connectivity | VerifyLLDPNeighbors | Verifies the connection status of the specified LLDP (Link Layer Discovery Protocol) neighbors. | ✅&nbsp;Success | - |
| c1-leaf4 | Connectivity | VerifyReachability | Verifies point-to-point reachability between Ethernet interfaces. | ✅&nbsp;Success | - |
| c1-leaf4 | Interfaces | VerifyIllegalLACP | Verifies there are no illegal LACP packets in port channels. | ✅&nbsp;Success | - |
| c1-leaf4 | Interfaces | VerifyInterfaceDiscards | Verifies that the interfaces packet discard counters are equal to zero. | ✅&nbsp;Success | - |
| c1-leaf4 | Interfaces | VerifyInterfaceErrDisabled | Verifies there are no interfaces in the errdisabled state. | ✅&nbsp;Success | - |
| c1-leaf4 | Interfaces | VerifyInterfaceErrors | Verifies that the interfaces error counters are equal to zero. | ✅&nbsp;Success | - |
| c1-leaf4 | Interfaces | VerifyInterfaceUtilization | Verifies that the utilization of interfaces is below a certain threshold. | ✅&nbsp;Success | - |
| c1-leaf4 | Interfaces | VerifyInterfacesStatus | Verifies the operational states of specified interfaces to ensure they match expected configurations. | ✅&nbsp;Success | - |
| c1-leaf4 | Interfaces | VerifyPortChannels | Verifies there are no inactive ports in port channels. | ✅&nbsp;Success | - |
| c1-leaf4 | MLAG | VerifyMlagConfigSanity | Verifies there are no MLAG config-sanity inconsistencies. | ✅&nbsp;Success | - |
| c1-leaf4 | MLAG | VerifyMlagInterfaces | Verifies there are no inactive or active-partial MLAG ports. | ✅&nbsp;Success | - |
| c1-leaf4 | MLAG | VerifyMlagStatus | Verifies the health status of the MLAG configuration. | ✅&nbsp;Success | - |
| c1-leaf4 | Routing | VerifyRoutingProtocolModel | Verifies the configured routing protocol model. | ✅&nbsp;Success | - |
| c1-leaf4 | STP | VerifySTPCounters | Verifies there is no errors in STP BPDU packets. | ✅&nbsp;Success | - |
| c1-leaf4 | System | VerifyAgentLogs | Verifies there are no agent crash reports. | ✅&nbsp;Success | - |
| c1-leaf4 | System | VerifyCoredump | Verifies there are no core dump files. | ✅&nbsp;Success | - |
| c1-leaf4 | System | VerifyFileSystemUtilization | Verifies that no partition is utilizing more than 75% of its disk space. | ✅&nbsp;Success | - |
| c1-leaf4 | System | VerifyMaintenance | Verifies that the device is not currently under or entering maintenance. | ✅&nbsp;Success | - |
| c1-leaf4 | System | VerifyMemoryUtilization | Verifies whether the memory utilization is below 75%. | ✅&nbsp;Success | - |
| c1-leaf4 | System | VerifyReloadCause | Verifies the last reload cause of the device. | ✅&nbsp;Success | - |
| c1-leaf4 | VXLAN | VerifyVxlanConfigSanity | Verifies there are no VXLAN config-sanity inconsistencies. | ✅&nbsp;Success | - |
| c1-leaf5 | BGP | VerifyBGPPeerSession | Verifies the session state of BGP peers. | ✅&nbsp;Success | - |
| c1-leaf5 | Configuration | VerifyRunningConfigDiffs | Verifies there is no difference between the running-config and the startup-config. | ✅&nbsp;Success | - |
| c1-leaf5 | Configuration | VerifyZeroTouch | Verifies ZeroTouch is disabled. | ✅&nbsp;Success | - |
| c1-leaf5 | Connectivity | VerifyLLDPNeighbors | Verifies the connection status of the specified LLDP (Link Layer Discovery Protocol) neighbors. | ✅&nbsp;Success | - |
| c1-leaf5 | Connectivity | VerifyReachability | Verifies point-to-point reachability between Ethernet interfaces. | ✅&nbsp;Success | - |
| c1-leaf5 | Interfaces | VerifyIllegalLACP | Verifies there are no illegal LACP packets in port channels. | ✅&nbsp;Success | - |
| c1-leaf5 | Interfaces | VerifyInterfaceDiscards | Verifies that the interfaces packet discard counters are equal to zero. | ✅&nbsp;Success | - |
| c1-leaf5 | Interfaces | VerifyInterfaceErrDisabled | Verifies there are no interfaces in the errdisabled state. | ✅&nbsp;Success | - |
| c1-leaf5 | Interfaces | VerifyInterfaceErrors | Verifies that the interfaces error counters are equal to zero. | ✅&nbsp;Success | - |
| c1-leaf5 | Interfaces | VerifyInterfaceUtilization | Verifies that the utilization of interfaces is below a certain threshold. | ✅&nbsp;Success | - |
| c1-leaf5 | Interfaces | VerifyInterfacesStatus | Verifies the operational states of specified interfaces to ensure they match expected configurations. | ✅&nbsp;Success | - |
| c1-leaf5 | Interfaces | VerifyPortChannels | Verifies there are no inactive ports in port channels. | ✅&nbsp;Success | - |
| c1-leaf5 | MLAG | VerifyMlagConfigSanity | Verifies there are no MLAG config-sanity inconsistencies. | ✅&nbsp;Success | - |
| c1-leaf5 | MLAG | VerifyMlagInterfaces | Verifies there are no inactive or active-partial MLAG ports. | ✅&nbsp;Success | - |
| c1-leaf5 | MLAG | VerifyMlagStatus | Verifies the health status of the MLAG configuration. | ✅&nbsp;Success | - |
| c1-leaf5 | Routing | VerifyRoutingProtocolModel | Verifies the configured routing protocol model. | ✅&nbsp;Success | - |
| c1-leaf5 | STP | VerifySTPCounters | Verifies there is no errors in STP BPDU packets. | ✅&nbsp;Success | - |
| c1-leaf5 | System | VerifyAgentLogs | Verifies there are no agent crash reports. | ✅&nbsp;Success | - |
| c1-leaf5 | System | VerifyCoredump | Verifies there are no core dump files. | ✅&nbsp;Success | - |
| c1-leaf5 | System | VerifyFileSystemUtilization | Verifies that no partition is utilizing more than 75% of its disk space. | ✅&nbsp;Success | - |
| c1-leaf5 | System | VerifyMaintenance | Verifies that the device is not currently under or entering maintenance. | ✅&nbsp;Success | - |
| c1-leaf5 | System | VerifyMemoryUtilization | Verifies whether the memory utilization is below 75%. | ✅&nbsp;Success | - |
| c1-leaf5 | System | VerifyReloadCause | Verifies the last reload cause of the device. | ✅&nbsp;Success | - |
| c1-leaf5 | VXLAN | VerifyVxlanConfigSanity | Verifies there are no VXLAN config-sanity inconsistencies. | ✅&nbsp;Success | - |
| c1-leaf6 | BGP | VerifyBGPPeerSession | Verifies the session state of BGP peers. | ✅&nbsp;Success | - |
| c1-leaf6 | Configuration | VerifyRunningConfigDiffs | Verifies there is no difference between the running-config and the startup-config. | ✅&nbsp;Success | - |
| c1-leaf6 | Configuration | VerifyZeroTouch | Verifies ZeroTouch is disabled. | ✅&nbsp;Success | - |
| c1-leaf6 | Connectivity | VerifyLLDPNeighbors | Verifies the connection status of the specified LLDP (Link Layer Discovery Protocol) neighbors. | ✅&nbsp;Success | - |
| c1-leaf6 | Connectivity | VerifyReachability | Verifies point-to-point reachability between Ethernet interfaces. | ✅&nbsp;Success | - |
| c1-leaf6 | Interfaces | VerifyIllegalLACP | Verifies there are no illegal LACP packets in port channels. | ✅&nbsp;Success | - |
| c1-leaf6 | Interfaces | VerifyInterfaceDiscards | Verifies that the interfaces packet discard counters are equal to zero. | ✅&nbsp;Success | - |
| c1-leaf6 | Interfaces | VerifyInterfaceErrDisabled | Verifies there are no interfaces in the errdisabled state. | ✅&nbsp;Success | - |
| c1-leaf6 | Interfaces | VerifyInterfaceErrors | Verifies that the interfaces error counters are equal to zero. | ✅&nbsp;Success | - |
| c1-leaf6 | Interfaces | VerifyInterfaceUtilization | Verifies that the utilization of interfaces is below a certain threshold. | ✅&nbsp;Success | - |
| c1-leaf6 | MLAG | VerifyMlagConfigSanity | Verifies there are no MLAG config-sanity inconsistencies. | ✅&nbsp;Success | - |
| c1-leaf6 | MLAG | VerifyMlagInterfaces | Verifies there are no inactive or active-partial MLAG ports. | ✅&nbsp;Success | - |
| c1-leaf6 | MLAG | VerifyMlagStatus | Verifies the health status of the MLAG configuration. | ✅&nbsp;Success | - |
| c1-leaf6 | Routing | VerifyRoutingProtocolModel | Verifies the configured routing protocol model. | ✅&nbsp;Success | - |
| c1-leaf6 | STP | VerifySTPCounters | Verifies there is no errors in STP BPDU packets. | ✅&nbsp;Success | - |
| c1-leaf6 | System | VerifyAgentLogs | Verifies there are no agent crash reports. | ✅&nbsp;Success | - |
| c1-leaf6 | System | VerifyCoredump | Verifies there are no core dump files. | ✅&nbsp;Success | - |
| c1-leaf6 | System | VerifyFileSystemUtilization | Verifies that no partition is utilizing more than 75% of its disk space. | ✅&nbsp;Success | - |
| c1-leaf6 | System | VerifyMaintenance | Verifies that the device is not currently under or entering maintenance. | ✅&nbsp;Success | - |
| c1-leaf6 | System | VerifyMemoryUtilization | Verifies whether the memory utilization is below 75%. | ✅&nbsp;Success | - |
| c1-leaf6 | System | VerifyReloadCause | Verifies the last reload cause of the device. | ✅&nbsp;Success | - |
| c1-leaf6 | VXLAN | VerifyVxlanConfigSanity | Verifies there are no VXLAN config-sanity inconsistencies. | ✅&nbsp;Success | - |
| c1-spine1 | BGP | VerifyBGPPeerSession | Verifies the session state of BGP peers. | ✅&nbsp;Success | - |
| c1-spine1 | Configuration | VerifyRunningConfigDiffs | Verifies there is no difference between the running-config and the startup-config. | ✅&nbsp;Success | - |
| c1-spine1 | Configuration | VerifyZeroTouch | Verifies ZeroTouch is disabled. | ✅&nbsp;Success | - |
| c1-spine1 | Connectivity | VerifyLLDPNeighbors | Verifies the connection status of the specified LLDP (Link Layer Discovery Protocol) neighbors. | ✅&nbsp;Success | - |
| c1-spine1 | Connectivity | VerifyReachability | Verifies point-to-point reachability between Ethernet interfaces. | ✅&nbsp;Success | - |
| c1-spine1 | Interfaces | VerifyInterfaceDiscards | Verifies that the interfaces packet discard counters are equal to zero. | ✅&nbsp;Success | - |
| c1-spine1 | Interfaces | VerifyInterfaceErrDisabled | Verifies there are no interfaces in the errdisabled state. | ✅&nbsp;Success | - |
| c1-spine1 | Interfaces | VerifyInterfaceErrors | Verifies that the interfaces error counters are equal to zero. | ✅&nbsp;Success | - |
| c1-spine1 | Interfaces | VerifyInterfaceUtilization | Verifies that the utilization of interfaces is below a certain threshold. | ✅&nbsp;Success | - |
| c1-spine1 | Interfaces | VerifyInterfacesStatus | Verifies the operational states of specified interfaces to ensure they match expected configurations. | ✅&nbsp;Success | - |
| c1-spine1 | Routing | VerifyRoutingProtocolModel | Verifies the configured routing protocol model. | ✅&nbsp;Success | - |
| c1-spine1 | STP | VerifySTPCounters | Verifies there is no errors in STP BPDU packets. | ✅&nbsp;Success | - |
| c1-spine1 | System | VerifyAgentLogs | Verifies there are no agent crash reports. | ✅&nbsp;Success | - |
| c1-spine1 | System | VerifyCoredump | Verifies there are no core dump files. | ✅&nbsp;Success | - |
| c1-spine1 | System | VerifyFileSystemUtilization | Verifies that no partition is utilizing more than 75% of its disk space. | ✅&nbsp;Success | - |
| c1-spine1 | System | VerifyMaintenance | Verifies that the device is not currently under or entering maintenance. | ✅&nbsp;Success | - |
| c1-spine1 | System | VerifyMemoryUtilization | Verifies whether the memory utilization is below 75%. | ✅&nbsp;Success | - |
| c1-spine1 | System | VerifyReloadCause | Verifies the last reload cause of the device. | ✅&nbsp;Success | - |
| c1-spine2 | BGP | VerifyBGPPeerSession | Verifies the session state of BGP peers. | ✅&nbsp;Success | - |
| c1-spine2 | Configuration | VerifyRunningConfigDiffs | Verifies there is no difference between the running-config and the startup-config. | ✅&nbsp;Success | - |
| c1-spine2 | Configuration | VerifyZeroTouch | Verifies ZeroTouch is disabled. | ✅&nbsp;Success | - |
| c1-spine2 | Connectivity | VerifyLLDPNeighbors | Verifies the connection status of the specified LLDP (Link Layer Discovery Protocol) neighbors. | ✅&nbsp;Success | - |
| c1-spine2 | Connectivity | VerifyReachability | Verifies point-to-point reachability between Ethernet interfaces. | ✅&nbsp;Success | - |
| c1-spine2 | Interfaces | VerifyInterfaceDiscards | Verifies that the interfaces packet discard counters are equal to zero. | ✅&nbsp;Success | - |
| c1-spine2 | Interfaces | VerifyInterfaceErrDisabled | Verifies there are no interfaces in the errdisabled state. | ✅&nbsp;Success | - |
| c1-spine2 | Interfaces | VerifyInterfaceErrors | Verifies that the interfaces error counters are equal to zero. | ✅&nbsp;Success | - |
| c1-spine2 | Interfaces | VerifyInterfaceUtilization | Verifies that the utilization of interfaces is below a certain threshold. | ✅&nbsp;Success | - |
| c1-spine2 | Interfaces | VerifyInterfacesStatus | Verifies the operational states of specified interfaces to ensure they match expected configurations. | ✅&nbsp;Success | - |
| c1-spine2 | Routing | VerifyRoutingProtocolModel | Verifies the configured routing protocol model. | ✅&nbsp;Success | - |
| c1-spine2 | STP | VerifySTPCounters | Verifies there is no errors in STP BPDU packets. | ✅&nbsp;Success | - |
| c1-spine2 | System | VerifyAgentLogs | Verifies there are no agent crash reports. | ✅&nbsp;Success | - |
| c1-spine2 | System | VerifyCoredump | Verifies there are no core dump files. | ✅&nbsp;Success | - |
| c1-spine2 | System | VerifyFileSystemUtilization | Verifies that no partition is utilizing more than 75% of its disk space. | ✅&nbsp;Success | - |
| c1-spine2 | System | VerifyMaintenance | Verifies that the device is not currently under or entering maintenance. | ✅&nbsp;Success | - |
| c1-spine2 | System | VerifyMemoryUtilization | Verifies whether the memory utilization is below 75%. | ✅&nbsp;Success | - |
| c1-spine2 | System | VerifyReloadCause | Verifies the last reload cause of the device. | ✅&nbsp;Success | - |
| c2-borderleaf1 | BGP | VerifyBGPPeerSession | Verifies the session state of BGP peers. | ✅&nbsp;Success | - |
| c2-borderleaf1 | Configuration | VerifyRunningConfigDiffs | Verifies there is no difference between the running-config and the startup-config. | ✅&nbsp;Success | - |
| c2-borderleaf1 | Configuration | VerifyZeroTouch | Verifies ZeroTouch is disabled. | ✅&nbsp;Success | - |
| c2-borderleaf1 | Connectivity | VerifyLLDPNeighbors | Verifies the connection status of the specified LLDP (Link Layer Discovery Protocol) neighbors. | ✅&nbsp;Success | - |
| c2-borderleaf1 | Connectivity | VerifyReachability | Verifies point-to-point reachability between Ethernet interfaces. | ✅&nbsp;Success | - |
| c2-borderleaf1 | Interfaces | VerifyIllegalLACP | Verifies there are no illegal LACP packets in port channels. | ✅&nbsp;Success | - |
| c2-borderleaf1 | Interfaces | VerifyInterfaceDiscards | Verifies that the interfaces packet discard counters are equal to zero. | ✅&nbsp;Success | - |
| c2-borderleaf1 | Interfaces | VerifyInterfaceErrDisabled | Verifies there are no interfaces in the errdisabled state. | ✅&nbsp;Success | - |
| c2-borderleaf1 | Interfaces | VerifyInterfaceErrors | Verifies that the interfaces error counters are equal to zero. | ✅&nbsp;Success | - |
| c2-borderleaf1 | Interfaces | VerifyInterfaceUtilization | Verifies that the utilization of interfaces is below a certain threshold. | ✅&nbsp;Success | - |
| c2-borderleaf1 | Interfaces | VerifyInterfacesStatus | Verifies the operational states of specified interfaces to ensure they match expected configurations. | ✅&nbsp;Success | - |
| c2-borderleaf1 | Interfaces | VerifyPortChannels | Verifies there are no inactive ports in port channels. | ✅&nbsp;Success | - |
| c2-borderleaf1 | MLAG | VerifyMlagConfigSanity | Verifies there are no MLAG config-sanity inconsistencies. | ✅&nbsp;Success | - |
| c2-borderleaf1 | MLAG | VerifyMlagInterfaces | Verifies there are no inactive or active-partial MLAG ports. | ✅&nbsp;Success | - |
| c2-borderleaf1 | MLAG | VerifyMlagStatus | Verifies the health status of the MLAG configuration. | ✅&nbsp;Success | - |
| c2-borderleaf1 | Routing | VerifyRoutingProtocolModel | Verifies the configured routing protocol model. | ✅&nbsp;Success | - |
| c2-borderleaf1 | STP | VerifySTPCounters | Verifies there is no errors in STP BPDU packets. | ✅&nbsp;Success | - |
| c2-borderleaf1 | System | VerifyAgentLogs | Verifies there are no agent crash reports. | ✅&nbsp;Success | - |
| c2-borderleaf1 | System | VerifyCoredump | Verifies there are no core dump files. | ✅&nbsp;Success | - |
| c2-borderleaf1 | System | VerifyFileSystemUtilization | Verifies that no partition is utilizing more than 75% of its disk space. | ✅&nbsp;Success | - |
| c2-borderleaf1 | System | VerifyMaintenance | Verifies that the device is not currently under or entering maintenance. | ✅&nbsp;Success | - |
| c2-borderleaf1 | System | VerifyMemoryUtilization | Verifies whether the memory utilization is below 75%. | ✅&nbsp;Success | - |
| c2-borderleaf1 | System | VerifyReloadCause | Verifies the last reload cause of the device. | ✅&nbsp;Success | - |
| c2-borderleaf1 | VXLAN | VerifyVxlanConfigSanity | Verifies there are no VXLAN config-sanity inconsistencies. | ✅&nbsp;Success | - |
| c2-borderleaf2 | BGP | VerifyBGPPeerSession | Verifies the session state of BGP peers. | ✅&nbsp;Success | - |
| c2-borderleaf2 | Configuration | VerifyRunningConfigDiffs | Verifies there is no difference between the running-config and the startup-config. | ✅&nbsp;Success | - |
| c2-borderleaf2 | Configuration | VerifyZeroTouch | Verifies ZeroTouch is disabled. | ✅&nbsp;Success | - |
| c2-borderleaf2 | Connectivity | VerifyLLDPNeighbors | Verifies the connection status of the specified LLDP (Link Layer Discovery Protocol) neighbors. | ✅&nbsp;Success | - |
| c2-borderleaf2 | Connectivity | VerifyReachability | Verifies point-to-point reachability between Ethernet interfaces. | ✅&nbsp;Success | - |
| c2-borderleaf2 | Interfaces | VerifyIllegalLACP | Verifies there are no illegal LACP packets in port channels. | ✅&nbsp;Success | - |
| c2-borderleaf2 | Interfaces | VerifyInterfaceDiscards | Verifies that the interfaces packet discard counters are equal to zero. | ✅&nbsp;Success | - |
| c2-borderleaf2 | Interfaces | VerifyInterfaceErrDisabled | Verifies there are no interfaces in the errdisabled state. | ✅&nbsp;Success | - |
| c2-borderleaf2 | Interfaces | VerifyInterfaceErrors | Verifies that the interfaces error counters are equal to zero. | ✅&nbsp;Success | - |
| c2-borderleaf2 | Interfaces | VerifyInterfaceUtilization | Verifies that the utilization of interfaces is below a certain threshold. | ✅&nbsp;Success | - |
| c2-borderleaf2 | Interfaces | VerifyInterfacesStatus | Verifies the operational states of specified interfaces to ensure they match expected configurations. | ✅&nbsp;Success | - |
| c2-borderleaf2 | Interfaces | VerifyPortChannels | Verifies there are no inactive ports in port channels. | ✅&nbsp;Success | - |
| c2-borderleaf2 | MLAG | VerifyMlagConfigSanity | Verifies there are no MLAG config-sanity inconsistencies. | ✅&nbsp;Success | - |
| c2-borderleaf2 | MLAG | VerifyMlagInterfaces | Verifies there are no inactive or active-partial MLAG ports. | ✅&nbsp;Success | - |
| c2-borderleaf2 | MLAG | VerifyMlagStatus | Verifies the health status of the MLAG configuration. | ✅&nbsp;Success | - |
| c2-borderleaf2 | Routing | VerifyRoutingProtocolModel | Verifies the configured routing protocol model. | ✅&nbsp;Success | - |
| c2-borderleaf2 | STP | VerifySTPCounters | Verifies there is no errors in STP BPDU packets. | ✅&nbsp;Success | - |
| c2-borderleaf2 | System | VerifyAgentLogs | Verifies there are no agent crash reports. | ✅&nbsp;Success | - |
| c2-borderleaf2 | System | VerifyCoredump | Verifies there are no core dump files. | ✅&nbsp;Success | - |
| c2-borderleaf2 | System | VerifyFileSystemUtilization | Verifies that no partition is utilizing more than 75% of its disk space. | ✅&nbsp;Success | - |
| c2-borderleaf2 | System | VerifyMaintenance | Verifies that the device is not currently under or entering maintenance. | ✅&nbsp;Success | - |
| c2-borderleaf2 | System | VerifyMemoryUtilization | Verifies whether the memory utilization is below 75%. | ✅&nbsp;Success | - |
| c2-borderleaf2 | System | VerifyReloadCause | Verifies the last reload cause of the device. | ✅&nbsp;Success | - |
| c2-borderleaf2 | VXLAN | VerifyVxlanConfigSanity | Verifies there are no VXLAN config-sanity inconsistencies. | ✅&nbsp;Success | - |
| c2-leaf1 | BGP | VerifyBGPPeerSession | Verifies the session state of BGP peers. | ✅&nbsp;Success | - |
| c2-leaf1 | Configuration | VerifyRunningConfigDiffs | Verifies there is no difference between the running-config and the startup-config. | ✅&nbsp;Success | - |
| c2-leaf1 | Configuration | VerifyZeroTouch | Verifies ZeroTouch is disabled. | ✅&nbsp;Success | - |
| c2-leaf1 | Connectivity | VerifyLLDPNeighbors | Verifies the connection status of the specified LLDP (Link Layer Discovery Protocol) neighbors. | ✅&nbsp;Success | - |
| c2-leaf1 | Connectivity | VerifyReachability | Verifies point-to-point reachability between Ethernet interfaces. | ✅&nbsp;Success | - |
| c2-leaf1 | Interfaces | VerifyIllegalLACP | Verifies there are no illegal LACP packets in port channels. | ✅&nbsp;Success | - |
| c2-leaf1 | Interfaces | VerifyInterfaceDiscards | Verifies that the interfaces packet discard counters are equal to zero. | ✅&nbsp;Success | - |
| c2-leaf1 | Interfaces | VerifyInterfaceErrDisabled | Verifies there are no interfaces in the errdisabled state. | ✅&nbsp;Success | - |
| c2-leaf1 | Interfaces | VerifyInterfaceErrors | Verifies that the interfaces error counters are equal to zero. | ✅&nbsp;Success | - |
| c2-leaf1 | Interfaces | VerifyInterfaceUtilization | Verifies that the utilization of interfaces is below a certain threshold. | ✅&nbsp;Success | - |
| c2-leaf1 | Interfaces | VerifyInterfacesStatus | Verifies the operational states of specified interfaces to ensure they match expected configurations. | ✅&nbsp;Success | - |
| c2-leaf1 | Interfaces | VerifyPortChannels | Verifies there are no inactive ports in port channels. | ✅&nbsp;Success | - |
| c2-leaf1 | MLAG | VerifyMlagConfigSanity | Verifies there are no MLAG config-sanity inconsistencies. | ✅&nbsp;Success | - |
| c2-leaf1 | MLAG | VerifyMlagInterfaces | Verifies there are no inactive or active-partial MLAG ports. | ✅&nbsp;Success | - |
| c2-leaf1 | MLAG | VerifyMlagStatus | Verifies the health status of the MLAG configuration. | ✅&nbsp;Success | - |
| c2-leaf1 | Routing | VerifyRoutingProtocolModel | Verifies the configured routing protocol model. | ✅&nbsp;Success | - |
| c2-leaf1 | STP | VerifySTPCounters | Verifies there is no errors in STP BPDU packets. | ✅&nbsp;Success | - |
| c2-leaf1 | System | VerifyAgentLogs | Verifies there are no agent crash reports. | ✅&nbsp;Success | - |
| c2-leaf1 | System | VerifyCoredump | Verifies there are no core dump files. | ✅&nbsp;Success | - |
| c2-leaf1 | System | VerifyFileSystemUtilization | Verifies that no partition is utilizing more than 75% of its disk space. | ✅&nbsp;Success | - |
| c2-leaf1 | System | VerifyMaintenance | Verifies that the device is not currently under or entering maintenance. | ✅&nbsp;Success | - |
| c2-leaf1 | System | VerifyMemoryUtilization | Verifies whether the memory utilization is below 75%. | ✅&nbsp;Success | - |
| c2-leaf1 | System | VerifyReloadCause | Verifies the last reload cause of the device. | ✅&nbsp;Success | - |
| c2-leaf1 | VXLAN | VerifyVxlanConfigSanity | Verifies there are no VXLAN config-sanity inconsistencies. | ✅&nbsp;Success | - |
| c2-leaf2 | BGP | VerifyBGPPeerSession | Verifies the session state of BGP peers. | ✅&nbsp;Success | - |
| c2-leaf2 | Configuration | VerifyRunningConfigDiffs | Verifies there is no difference between the running-config and the startup-config. | ✅&nbsp;Success | - |
| c2-leaf2 | Configuration | VerifyZeroTouch | Verifies ZeroTouch is disabled. | ✅&nbsp;Success | - |
| c2-leaf2 | Connectivity | VerifyLLDPNeighbors | Verifies the connection status of the specified LLDP (Link Layer Discovery Protocol) neighbors. | ✅&nbsp;Success | - |
| c2-leaf2 | Connectivity | VerifyReachability | Verifies point-to-point reachability between Ethernet interfaces. | ✅&nbsp;Success | - |
| c2-leaf2 | Interfaces | VerifyIllegalLACP | Verifies there are no illegal LACP packets in port channels. | ✅&nbsp;Success | - |
| c2-leaf2 | Interfaces | VerifyInterfaceDiscards | Verifies that the interfaces packet discard counters are equal to zero. | ✅&nbsp;Success | - |
| c2-leaf2 | Interfaces | VerifyInterfaceErrDisabled | Verifies there are no interfaces in the errdisabled state. | ✅&nbsp;Success | - |
| c2-leaf2 | Interfaces | VerifyInterfaceErrors | Verifies that the interfaces error counters are equal to zero. | ✅&nbsp;Success | - |
| c2-leaf2 | Interfaces | VerifyInterfaceUtilization | Verifies that the utilization of interfaces is below a certain threshold. | ✅&nbsp;Success | - |
| c2-leaf2 | Interfaces | VerifyInterfacesStatus | Verifies the operational states of specified interfaces to ensure they match expected configurations. | ✅&nbsp;Success | - |
| c2-leaf2 | Interfaces | VerifyPortChannels | Verifies there are no inactive ports in port channels. | ✅&nbsp;Success | - |
| c2-leaf2 | MLAG | VerifyMlagConfigSanity | Verifies there are no MLAG config-sanity inconsistencies. | ✅&nbsp;Success | - |
| c2-leaf2 | MLAG | VerifyMlagInterfaces | Verifies there are no inactive or active-partial MLAG ports. | ✅&nbsp;Success | - |
| c2-leaf2 | MLAG | VerifyMlagStatus | Verifies the health status of the MLAG configuration. | ✅&nbsp;Success | - |
| c2-leaf2 | Routing | VerifyRoutingProtocolModel | Verifies the configured routing protocol model. | ✅&nbsp;Success | - |
| c2-leaf2 | STP | VerifySTPCounters | Verifies there is no errors in STP BPDU packets. | ✅&nbsp;Success | - |
| c2-leaf2 | System | VerifyAgentLogs | Verifies there are no agent crash reports. | ✅&nbsp;Success | - |
| c2-leaf2 | System | VerifyCoredump | Verifies there are no core dump files. | ✅&nbsp;Success | - |
| c2-leaf2 | System | VerifyFileSystemUtilization | Verifies that no partition is utilizing more than 75% of its disk space. | ✅&nbsp;Success | - |
| c2-leaf2 | System | VerifyMaintenance | Verifies that the device is not currently under or entering maintenance. | ✅&nbsp;Success | - |
| c2-leaf2 | System | VerifyMemoryUtilization | Verifies whether the memory utilization is below 75%. | ✅&nbsp;Success | - |
| c2-leaf2 | System | VerifyReloadCause | Verifies the last reload cause of the device. | ✅&nbsp;Success | - |
| c2-leaf2 | VXLAN | VerifyVxlanConfigSanity | Verifies there are no VXLAN config-sanity inconsistencies. | ✅&nbsp;Success | - |
| c2-leaf3 | BGP | VerifyBGPPeerSession | Verifies the session state of BGP peers. | ✅&nbsp;Success | - |
| c2-leaf3 | Configuration | VerifyRunningConfigDiffs | Verifies there is no difference between the running-config and the startup-config. | ✅&nbsp;Success | - |
| c2-leaf3 | Configuration | VerifyZeroTouch | Verifies ZeroTouch is disabled. | ✅&nbsp;Success | - |
| c2-leaf3 | Connectivity | VerifyLLDPNeighbors | Verifies the connection status of the specified LLDP (Link Layer Discovery Protocol) neighbors. | ✅&nbsp;Success | - |
| c2-leaf3 | Connectivity | VerifyReachability | Verifies point-to-point reachability between Ethernet interfaces. | ✅&nbsp;Success | - |
| c2-leaf3 | Interfaces | VerifyIllegalLACP | Verifies there are no illegal LACP packets in port channels. | ✅&nbsp;Success | - |
| c2-leaf3 | Interfaces | VerifyInterfaceDiscards | Verifies that the interfaces packet discard counters are equal to zero. | ✅&nbsp;Success | - |
| c2-leaf3 | Interfaces | VerifyInterfaceErrDisabled | Verifies there are no interfaces in the errdisabled state. | ✅&nbsp;Success | - |
| c2-leaf3 | Interfaces | VerifyInterfaceErrors | Verifies that the interfaces error counters are equal to zero. | ✅&nbsp;Success | - |
| c2-leaf3 | Interfaces | VerifyInterfaceUtilization | Verifies that the utilization of interfaces is below a certain threshold. | ✅&nbsp;Success | - |
| c2-leaf3 | Interfaces | VerifyInterfacesStatus | Verifies the operational states of specified interfaces to ensure they match expected configurations. | ✅&nbsp;Success | - |
| c2-leaf3 | Interfaces | VerifyPortChannels | Verifies there are no inactive ports in port channels. | ✅&nbsp;Success | - |
| c2-leaf3 | MLAG | VerifyMlagConfigSanity | Verifies there are no MLAG config-sanity inconsistencies. | ✅&nbsp;Success | - |
| c2-leaf3 | MLAG | VerifyMlagInterfaces | Verifies there are no inactive or active-partial MLAG ports. | ✅&nbsp;Success | - |
| c2-leaf3 | MLAG | VerifyMlagStatus | Verifies the health status of the MLAG configuration. | ✅&nbsp;Success | - |
| c2-leaf3 | Routing | VerifyRoutingProtocolModel | Verifies the configured routing protocol model. | ✅&nbsp;Success | - |
| c2-leaf3 | STP | VerifySTPCounters | Verifies there is no errors in STP BPDU packets. | ✅&nbsp;Success | - |
| c2-leaf3 | System | VerifyAgentLogs | Verifies there are no agent crash reports. | ✅&nbsp;Success | - |
| c2-leaf3 | System | VerifyCoredump | Verifies there are no core dump files. | ✅&nbsp;Success | - |
| c2-leaf3 | System | VerifyFileSystemUtilization | Verifies that no partition is utilizing more than 75% of its disk space. | ✅&nbsp;Success | - |
| c2-leaf3 | System | VerifyMaintenance | Verifies that the device is not currently under or entering maintenance. | ✅&nbsp;Success | - |
| c2-leaf3 | System | VerifyMemoryUtilization | Verifies whether the memory utilization is below 75%. | ✅&nbsp;Success | - |
| c2-leaf3 | System | VerifyReloadCause | Verifies the last reload cause of the device. | ✅&nbsp;Success | - |
| c2-leaf3 | VXLAN | VerifyVxlanConfigSanity | Verifies there are no VXLAN config-sanity inconsistencies. | ✅&nbsp;Success | - |
| c2-leaf4 | BGP | VerifyBGPPeerSession | Verifies the session state of BGP peers. | ✅&nbsp;Success | - |
| c2-leaf4 | Configuration | VerifyRunningConfigDiffs | Verifies there is no difference between the running-config and the startup-config. | ✅&nbsp;Success | - |
| c2-leaf4 | Configuration | VerifyZeroTouch | Verifies ZeroTouch is disabled. | ✅&nbsp;Success | - |
| c2-leaf4 | Connectivity | VerifyLLDPNeighbors | Verifies the connection status of the specified LLDP (Link Layer Discovery Protocol) neighbors. | ✅&nbsp;Success | - |
| c2-leaf4 | Connectivity | VerifyReachability | Verifies point-to-point reachability between Ethernet interfaces. | ✅&nbsp;Success | - |
| c2-leaf4 | Interfaces | VerifyIllegalLACP | Verifies there are no illegal LACP packets in port channels. | ✅&nbsp;Success | - |
| c2-leaf4 | Interfaces | VerifyInterfaceDiscards | Verifies that the interfaces packet discard counters are equal to zero. | ✅&nbsp;Success | - |
| c2-leaf4 | Interfaces | VerifyInterfaceErrDisabled | Verifies there are no interfaces in the errdisabled state. | ✅&nbsp;Success | - |
| c2-leaf4 | Interfaces | VerifyInterfaceErrors | Verifies that the interfaces error counters are equal to zero. | ✅&nbsp;Success | - |
| c2-leaf4 | Interfaces | VerifyInterfaceUtilization | Verifies that the utilization of interfaces is below a certain threshold. | ✅&nbsp;Success | - |
| c2-leaf4 | Interfaces | VerifyInterfacesStatus | Verifies the operational states of specified interfaces to ensure they match expected configurations. | ✅&nbsp;Success | - |
| c2-leaf4 | Interfaces | VerifyPortChannels | Verifies there are no inactive ports in port channels. | ✅&nbsp;Success | - |
| c2-leaf4 | MLAG | VerifyMlagConfigSanity | Verifies there are no MLAG config-sanity inconsistencies. | ✅&nbsp;Success | - |
| c2-leaf4 | MLAG | VerifyMlagInterfaces | Verifies there are no inactive or active-partial MLAG ports. | ✅&nbsp;Success | - |
| c2-leaf4 | MLAG | VerifyMlagStatus | Verifies the health status of the MLAG configuration. | ✅&nbsp;Success | - |
| c2-leaf4 | Routing | VerifyRoutingProtocolModel | Verifies the configured routing protocol model. | ✅&nbsp;Success | - |
| c2-leaf4 | STP | VerifySTPCounters | Verifies there is no errors in STP BPDU packets. | ✅&nbsp;Success | - |
| c2-leaf4 | System | VerifyAgentLogs | Verifies there are no agent crash reports. | ✅&nbsp;Success | - |
| c2-leaf4 | System | VerifyCoredump | Verifies there are no core dump files. | ✅&nbsp;Success | - |
| c2-leaf4 | System | VerifyFileSystemUtilization | Verifies that no partition is utilizing more than 75% of its disk space. | ✅&nbsp;Success | - |
| c2-leaf4 | System | VerifyMaintenance | Verifies that the device is not currently under or entering maintenance. | ✅&nbsp;Success | - |
| c2-leaf4 | System | VerifyMemoryUtilization | Verifies whether the memory utilization is below 75%. | ✅&nbsp;Success | - |
| c2-leaf4 | System | VerifyReloadCause | Verifies the last reload cause of the device. | ✅&nbsp;Success | - |
| c2-leaf4 | VXLAN | VerifyVxlanConfigSanity | Verifies there are no VXLAN config-sanity inconsistencies. | ✅&nbsp;Success | - |
| c2-leaf5 | BGP | VerifyBGPPeerSession | Verifies the session state of BGP peers. | ✅&nbsp;Success | - |
| c2-leaf5 | Configuration | VerifyRunningConfigDiffs | Verifies there is no difference between the running-config and the startup-config. | ✅&nbsp;Success | - |
| c2-leaf5 | Configuration | VerifyZeroTouch | Verifies ZeroTouch is disabled. | ✅&nbsp;Success | - |
| c2-leaf5 | Connectivity | VerifyLLDPNeighbors | Verifies the connection status of the specified LLDP (Link Layer Discovery Protocol) neighbors. | ✅&nbsp;Success | - |
| c2-leaf5 | Connectivity | VerifyReachability | Verifies point-to-point reachability between Ethernet interfaces. | ✅&nbsp;Success | - |
| c2-leaf5 | Interfaces | VerifyIllegalLACP | Verifies there are no illegal LACP packets in port channels. | ✅&nbsp;Success | - |
| c2-leaf5 | Interfaces | VerifyInterfaceDiscards | Verifies that the interfaces packet discard counters are equal to zero. | ✅&nbsp;Success | - |
| c2-leaf5 | Interfaces | VerifyInterfaceErrDisabled | Verifies there are no interfaces in the errdisabled state. | ✅&nbsp;Success | - |
| c2-leaf5 | Interfaces | VerifyInterfaceErrors | Verifies that the interfaces error counters are equal to zero. | ✅&nbsp;Success | - |
| c2-leaf5 | Interfaces | VerifyInterfaceUtilization | Verifies that the utilization of interfaces is below a certain threshold. | ✅&nbsp;Success | - |
| c2-leaf5 | Interfaces | VerifyInterfacesStatus | Verifies the operational states of specified interfaces to ensure they match expected configurations. | ✅&nbsp;Success | - |
| c2-leaf5 | Interfaces | VerifyPortChannels | Verifies there are no inactive ports in port channels. | ✅&nbsp;Success | - |
| c2-leaf5 | MLAG | VerifyMlagConfigSanity | Verifies there are no MLAG config-sanity inconsistencies. | ✅&nbsp;Success | - |
| c2-leaf5 | MLAG | VerifyMlagInterfaces | Verifies there are no inactive or active-partial MLAG ports. | ✅&nbsp;Success | - |
| c2-leaf5 | MLAG | VerifyMlagStatus | Verifies the health status of the MLAG configuration. | ✅&nbsp;Success | - |
| c2-leaf5 | Routing | VerifyRoutingProtocolModel | Verifies the configured routing protocol model. | ✅&nbsp;Success | - |
| c2-leaf5 | STP | VerifySTPCounters | Verifies there is no errors in STP BPDU packets. | ✅&nbsp;Success | - |
| c2-leaf5 | System | VerifyAgentLogs | Verifies there are no agent crash reports. | ✅&nbsp;Success | - |
| c2-leaf5 | System | VerifyCoredump | Verifies there are no core dump files. | ✅&nbsp;Success | - |
| c2-leaf5 | System | VerifyFileSystemUtilization | Verifies that no partition is utilizing more than 75% of its disk space. | ✅&nbsp;Success | - |
| c2-leaf5 | System | VerifyMaintenance | Verifies that the device is not currently under or entering maintenance. | ✅&nbsp;Success | - |
| c2-leaf5 | System | VerifyMemoryUtilization | Verifies whether the memory utilization is below 75%. | ✅&nbsp;Success | - |
| c2-leaf5 | System | VerifyReloadCause | Verifies the last reload cause of the device. | ✅&nbsp;Success | - |
| c2-leaf5 | VXLAN | VerifyVxlanConfigSanity | Verifies there are no VXLAN config-sanity inconsistencies. | ✅&nbsp;Success | - |
| c2-leaf6 | BGP | VerifyBGPPeerSession | Verifies the session state of BGP peers. | ✅&nbsp;Success | - |
| c2-leaf6 | Configuration | VerifyRunningConfigDiffs | Verifies there is no difference between the running-config and the startup-config. | ✅&nbsp;Success | - |
| c2-leaf6 | Configuration | VerifyZeroTouch | Verifies ZeroTouch is disabled. | ✅&nbsp;Success | - |
| c2-leaf6 | Connectivity | VerifyLLDPNeighbors | Verifies the connection status of the specified LLDP (Link Layer Discovery Protocol) neighbors. | ✅&nbsp;Success | - |
| c2-leaf6 | Connectivity | VerifyReachability | Verifies point-to-point reachability between Ethernet interfaces. | ✅&nbsp;Success | - |
| c2-leaf6 | Interfaces | VerifyIllegalLACP | Verifies there are no illegal LACP packets in port channels. | ✅&nbsp;Success | - |
| c2-leaf6 | Interfaces | VerifyInterfaceDiscards | Verifies that the interfaces packet discard counters are equal to zero. | ✅&nbsp;Success | - |
| c2-leaf6 | Interfaces | VerifyInterfaceErrDisabled | Verifies there are no interfaces in the errdisabled state. | ✅&nbsp;Success | - |
| c2-leaf6 | Interfaces | VerifyInterfaceErrors | Verifies that the interfaces error counters are equal to zero. | ✅&nbsp;Success | - |
| c2-leaf6 | Interfaces | VerifyInterfaceUtilization | Verifies that the utilization of interfaces is below a certain threshold. | ✅&nbsp;Success | - |
| c2-leaf6 | MLAG | VerifyMlagConfigSanity | Verifies there are no MLAG config-sanity inconsistencies. | ✅&nbsp;Success | - |
| c2-leaf6 | MLAG | VerifyMlagInterfaces | Verifies there are no inactive or active-partial MLAG ports. | ✅&nbsp;Success | - |
| c2-leaf6 | MLAG | VerifyMlagStatus | Verifies the health status of the MLAG configuration. | ✅&nbsp;Success | - |
| c2-leaf6 | Routing | VerifyRoutingProtocolModel | Verifies the configured routing protocol model. | ✅&nbsp;Success | - |
| c2-leaf6 | STP | VerifySTPCounters | Verifies there is no errors in STP BPDU packets. | ✅&nbsp;Success | - |
| c2-leaf6 | System | VerifyAgentLogs | Verifies there are no agent crash reports. | ✅&nbsp;Success | - |
| c2-leaf6 | System | VerifyCoredump | Verifies there are no core dump files. | ✅&nbsp;Success | - |
| c2-leaf6 | System | VerifyFileSystemUtilization | Verifies that no partition is utilizing more than 75% of its disk space. | ✅&nbsp;Success | - |
| c2-leaf6 | System | VerifyMaintenance | Verifies that the device is not currently under or entering maintenance. | ✅&nbsp;Success | - |
| c2-leaf6 | System | VerifyMemoryUtilization | Verifies whether the memory utilization is below 75%. | ✅&nbsp;Success | - |
| c2-leaf6 | System | VerifyReloadCause | Verifies the last reload cause of the device. | ✅&nbsp;Success | - |
| c2-leaf6 | VXLAN | VerifyVxlanConfigSanity | Verifies there are no VXLAN config-sanity inconsistencies. | ✅&nbsp;Success | - |
| c2-spine1 | BGP | VerifyBGPPeerSession | Verifies the session state of BGP peers. | ✅&nbsp;Success | - |
| c2-spine1 | Configuration | VerifyRunningConfigDiffs | Verifies there is no difference between the running-config and the startup-config. | ✅&nbsp;Success | - |
| c2-spine1 | Configuration | VerifyZeroTouch | Verifies ZeroTouch is disabled. | ✅&nbsp;Success | - |
| c2-spine1 | Connectivity | VerifyLLDPNeighbors | Verifies the connection status of the specified LLDP (Link Layer Discovery Protocol) neighbors. | ✅&nbsp;Success | - |
| c2-spine1 | Connectivity | VerifyReachability | Verifies point-to-point reachability between Ethernet interfaces. | ✅&nbsp;Success | - |
| c2-spine1 | Interfaces | VerifyInterfaceDiscards | Verifies that the interfaces packet discard counters are equal to zero. | ✅&nbsp;Success | - |
| c2-spine1 | Interfaces | VerifyInterfaceErrDisabled | Verifies there are no interfaces in the errdisabled state. | ✅&nbsp;Success | - |
| c2-spine1 | Interfaces | VerifyInterfaceErrors | Verifies that the interfaces error counters are equal to zero. | ✅&nbsp;Success | - |
| c2-spine1 | Interfaces | VerifyInterfaceUtilization | Verifies that the utilization of interfaces is below a certain threshold. | ✅&nbsp;Success | - |
| c2-spine1 | Interfaces | VerifyInterfacesStatus | Verifies the operational states of specified interfaces to ensure they match expected configurations. | ✅&nbsp;Success | - |
| c2-spine1 | Routing | VerifyRoutingProtocolModel | Verifies the configured routing protocol model. | ✅&nbsp;Success | - |
| c2-spine1 | STP | VerifySTPCounters | Verifies there is no errors in STP BPDU packets. | ✅&nbsp;Success | - |
| c2-spine1 | System | VerifyAgentLogs | Verifies there are no agent crash reports. | ✅&nbsp;Success | - |
| c2-spine1 | System | VerifyCoredump | Verifies there are no core dump files. | ✅&nbsp;Success | - |
| c2-spine1 | System | VerifyFileSystemUtilization | Verifies that no partition is utilizing more than 75% of its disk space. | ✅&nbsp;Success | - |
| c2-spine1 | System | VerifyMaintenance | Verifies that the device is not currently under or entering maintenance. | ✅&nbsp;Success | - |
| c2-spine1 | System | VerifyMemoryUtilization | Verifies whether the memory utilization is below 75%. | ✅&nbsp;Success | - |
| c2-spine1 | System | VerifyReloadCause | Verifies the last reload cause of the device. | ✅&nbsp;Success | - |
| c2-spine2 | BGP | VerifyBGPPeerSession | Verifies the session state of BGP peers. | ✅&nbsp;Success | - |
| c2-spine2 | Configuration | VerifyRunningConfigDiffs | Verifies there is no difference between the running-config and the startup-config. | ✅&nbsp;Success | - |
| c2-spine2 | Configuration | VerifyZeroTouch | Verifies ZeroTouch is disabled. | ✅&nbsp;Success | - |
| c2-spine2 | Connectivity | VerifyLLDPNeighbors | Verifies the connection status of the specified LLDP (Link Layer Discovery Protocol) neighbors. | ✅&nbsp;Success | - |
| c2-spine2 | Connectivity | VerifyReachability | Verifies point-to-point reachability between Ethernet interfaces. | ✅&nbsp;Success | - |
| c2-spine2 | Interfaces | VerifyInterfaceDiscards | Verifies that the interfaces packet discard counters are equal to zero. | ✅&nbsp;Success | - |
| c2-spine2 | Interfaces | VerifyInterfaceErrDisabled | Verifies there are no interfaces in the errdisabled state. | ✅&nbsp;Success | - |
| c2-spine2 | Interfaces | VerifyInterfaceErrors | Verifies that the interfaces error counters are equal to zero. | ✅&nbsp;Success | - |
| c2-spine2 | Interfaces | VerifyInterfaceUtilization | Verifies that the utilization of interfaces is below a certain threshold. | ✅&nbsp;Success | - |
| c2-spine2 | Interfaces | VerifyInterfacesStatus | Verifies the operational states of specified interfaces to ensure they match expected configurations. | ✅&nbsp;Success | - |
| c2-spine2 | Routing | VerifyRoutingProtocolModel | Verifies the configured routing protocol model. | ✅&nbsp;Success | - |
| c2-spine2 | STP | VerifySTPCounters | Verifies there is no errors in STP BPDU packets. | ✅&nbsp;Success | - |
| c2-spine2 | System | VerifyAgentLogs | Verifies there are no agent crash reports. | ✅&nbsp;Success | - |
| c2-spine2 | System | VerifyCoredump | Verifies there are no core dump files. | ✅&nbsp;Success | - |
| c2-spine2 | System | VerifyFileSystemUtilization | Verifies that no partition is utilizing more than 75% of its disk space. | ✅&nbsp;Success | - |
| c2-spine2 | System | VerifyMaintenance | Verifies that the device is not currently under or entering maintenance. | ✅&nbsp;Success | - |
| c2-spine2 | System | VerifyMemoryUtilization | Verifies whether the memory utilization is below 75%. | ✅&nbsp;Success | - |
| c2-spine2 | System | VerifyReloadCause | Verifies the last reload cause of the device. | ✅&nbsp;Success | - |
| c3-borderleaf1 | BGP | VerifyBGPPeerSession | Verifies the session state of BGP peers. | ✅&nbsp;Success | - |
| c3-borderleaf1 | Configuration | VerifyRunningConfigDiffs | Verifies there is no difference between the running-config and the startup-config. | ✅&nbsp;Success | - |
| c3-borderleaf1 | Configuration | VerifyZeroTouch | Verifies ZeroTouch is disabled. | ✅&nbsp;Success | - |
| c3-borderleaf1 | Connectivity | VerifyLLDPNeighbors | Verifies the connection status of the specified LLDP (Link Layer Discovery Protocol) neighbors. | ✅&nbsp;Success | - |
| c3-borderleaf1 | Connectivity | VerifyReachability | Verifies point-to-point reachability between Ethernet interfaces. | ✅&nbsp;Success | - |
| c3-borderleaf1 | Interfaces | VerifyIllegalLACP | Verifies there are no illegal LACP packets in port channels. | ✅&nbsp;Success | - |
| c3-borderleaf1 | Interfaces | VerifyInterfaceDiscards | Verifies that the interfaces packet discard counters are equal to zero. | ✅&nbsp;Success | - |
| c3-borderleaf1 | Interfaces | VerifyInterfaceErrDisabled | Verifies there are no interfaces in the errdisabled state. | ✅&nbsp;Success | - |
| c3-borderleaf1 | Interfaces | VerifyInterfaceErrors | Verifies that the interfaces error counters are equal to zero. | ✅&nbsp;Success | - |
| c3-borderleaf1 | Interfaces | VerifyInterfaceUtilization | Verifies that the utilization of interfaces is below a certain threshold. | ✅&nbsp;Success | - |
| c3-borderleaf1 | Interfaces | VerifyInterfacesStatus | Verifies the operational states of specified interfaces to ensure they match expected configurations. | ✅&nbsp;Success | - |
| c3-borderleaf1 | Interfaces | VerifyPortChannels | Verifies there are no inactive ports in port channels. | ✅&nbsp;Success | - |
| c3-borderleaf1 | MLAG | VerifyMlagConfigSanity | Verifies there are no MLAG config-sanity inconsistencies. | ✅&nbsp;Success | - |
| c3-borderleaf1 | MLAG | VerifyMlagInterfaces | Verifies there are no inactive or active-partial MLAG ports. | ✅&nbsp;Success | - |
| c3-borderleaf1 | MLAG | VerifyMlagStatus | Verifies the health status of the MLAG configuration. | ✅&nbsp;Success | - |
| c3-borderleaf1 | Routing | VerifyRoutingProtocolModel | Verifies the configured routing protocol model. | ✅&nbsp;Success | - |
| c3-borderleaf1 | STP | VerifySTPCounters | Verifies there is no errors in STP BPDU packets. | ✅&nbsp;Success | - |
| c3-borderleaf1 | System | VerifyAgentLogs | Verifies there are no agent crash reports. | ✅&nbsp;Success | - |
| c3-borderleaf1 | System | VerifyCoredump | Verifies there are no core dump files. | ✅&nbsp;Success | - |
| c3-borderleaf1 | System | VerifyFileSystemUtilization | Verifies that no partition is utilizing more than 75% of its disk space. | ✅&nbsp;Success | - |
| c3-borderleaf1 | System | VerifyMaintenance | Verifies that the device is not currently under or entering maintenance. | ✅&nbsp;Success | - |
| c3-borderleaf1 | System | VerifyMemoryUtilization | Verifies whether the memory utilization is below 75%. | ✅&nbsp;Success | - |
| c3-borderleaf1 | System | VerifyReloadCause | Verifies the last reload cause of the device. | ✅&nbsp;Success | - |
| c3-borderleaf1 | VXLAN | VerifyVxlanConfigSanity | Verifies there are no VXLAN config-sanity inconsistencies. | ✅&nbsp;Success | - |
| c3-borderleaf2 | BGP | VerifyBGPPeerSession | Verifies the session state of BGP peers. | ✅&nbsp;Success | - |
| c3-borderleaf2 | Configuration | VerifyRunningConfigDiffs | Verifies there is no difference between the running-config and the startup-config. | ✅&nbsp;Success | - |
| c3-borderleaf2 | Configuration | VerifyZeroTouch | Verifies ZeroTouch is disabled. | ✅&nbsp;Success | - |
| c3-borderleaf2 | Connectivity | VerifyLLDPNeighbors | Verifies the connection status of the specified LLDP (Link Layer Discovery Protocol) neighbors. | ✅&nbsp;Success | - |
| c3-borderleaf2 | Connectivity | VerifyReachability | Verifies point-to-point reachability between Ethernet interfaces. | ✅&nbsp;Success | - |
| c3-borderleaf2 | Interfaces | VerifyIllegalLACP | Verifies there are no illegal LACP packets in port channels. | ✅&nbsp;Success | - |
| c3-borderleaf2 | Interfaces | VerifyInterfaceDiscards | Verifies that the interfaces packet discard counters are equal to zero. | ✅&nbsp;Success | - |
| c3-borderleaf2 | Interfaces | VerifyInterfaceErrDisabled | Verifies there are no interfaces in the errdisabled state. | ✅&nbsp;Success | - |
| c3-borderleaf2 | Interfaces | VerifyInterfaceErrors | Verifies that the interfaces error counters are equal to zero. | ✅&nbsp;Success | - |
| c3-borderleaf2 | Interfaces | VerifyInterfaceUtilization | Verifies that the utilization of interfaces is below a certain threshold. | ✅&nbsp;Success | - |
| c3-borderleaf2 | Interfaces | VerifyInterfacesStatus | Verifies the operational states of specified interfaces to ensure they match expected configurations. | ✅&nbsp;Success | - |
| c3-borderleaf2 | Interfaces | VerifyPortChannels | Verifies there are no inactive ports in port channels. | ✅&nbsp;Success | - |
| c3-borderleaf2 | MLAG | VerifyMlagConfigSanity | Verifies there are no MLAG config-sanity inconsistencies. | ✅&nbsp;Success | - |
| c3-borderleaf2 | MLAG | VerifyMlagInterfaces | Verifies there are no inactive or active-partial MLAG ports. | ✅&nbsp;Success | - |
| c3-borderleaf2 | MLAG | VerifyMlagStatus | Verifies the health status of the MLAG configuration. | ✅&nbsp;Success | - |
| c3-borderleaf2 | Routing | VerifyRoutingProtocolModel | Verifies the configured routing protocol model. | ✅&nbsp;Success | - |
| c3-borderleaf2 | STP | VerifySTPCounters | Verifies there is no errors in STP BPDU packets. | ✅&nbsp;Success | - |
| c3-borderleaf2 | System | VerifyAgentLogs | Verifies there are no agent crash reports. | ✅&nbsp;Success | - |
| c3-borderleaf2 | System | VerifyCoredump | Verifies there are no core dump files. | ✅&nbsp;Success | - |
| c3-borderleaf2 | System | VerifyFileSystemUtilization | Verifies that no partition is utilizing more than 75% of its disk space. | ✅&nbsp;Success | - |
| c3-borderleaf2 | System | VerifyMaintenance | Verifies that the device is not currently under or entering maintenance. | ✅&nbsp;Success | - |
| c3-borderleaf2 | System | VerifyMemoryUtilization | Verifies whether the memory utilization is below 75%. | ✅&nbsp;Success | - |
| c3-borderleaf2 | System | VerifyReloadCause | Verifies the last reload cause of the device. | ✅&nbsp;Success | - |
| c3-borderleaf2 | VXLAN | VerifyVxlanConfigSanity | Verifies there are no VXLAN config-sanity inconsistencies. | ✅&nbsp;Success | - |
| c3-leaf1 | BGP | VerifyBGPPeerSession | Verifies the session state of BGP peers. | ✅&nbsp;Success | - |
| c3-leaf1 | Configuration | VerifyRunningConfigDiffs | Verifies there is no difference between the running-config and the startup-config. | ✅&nbsp;Success | - |
| c3-leaf1 | Configuration | VerifyZeroTouch | Verifies ZeroTouch is disabled. | ✅&nbsp;Success | - |
| c3-leaf1 | Connectivity | VerifyLLDPNeighbors | Verifies the connection status of the specified LLDP (Link Layer Discovery Protocol) neighbors. | ✅&nbsp;Success | - |
| c3-leaf1 | Connectivity | VerifyReachability | Verifies point-to-point reachability between Ethernet interfaces. | ✅&nbsp;Success | - |
| c3-leaf1 | Interfaces | VerifyIllegalLACP | Verifies there are no illegal LACP packets in port channels. | ✅&nbsp;Success | - |
| c3-leaf1 | Interfaces | VerifyInterfaceDiscards | Verifies that the interfaces packet discard counters are equal to zero. | ✅&nbsp;Success | - |
| c3-leaf1 | Interfaces | VerifyInterfaceErrDisabled | Verifies there are no interfaces in the errdisabled state. | ✅&nbsp;Success | - |
| c3-leaf1 | Interfaces | VerifyInterfaceErrors | Verifies that the interfaces error counters are equal to zero. | ✅&nbsp;Success | - |
| c3-leaf1 | Interfaces | VerifyInterfaceUtilization | Verifies that the utilization of interfaces is below a certain threshold. | ✅&nbsp;Success | - |
| c3-leaf1 | Interfaces | VerifyInterfacesStatus | Verifies the operational states of specified interfaces to ensure they match expected configurations. | ✅&nbsp;Success | - |
| c3-leaf1 | Interfaces | VerifyPortChannels | Verifies there are no inactive ports in port channels. | ✅&nbsp;Success | - |
| c3-leaf1 | MLAG | VerifyMlagConfigSanity | Verifies there are no MLAG config-sanity inconsistencies. | ✅&nbsp;Success | - |
| c3-leaf1 | MLAG | VerifyMlagInterfaces | Verifies there are no inactive or active-partial MLAG ports. | ✅&nbsp;Success | - |
| c3-leaf1 | MLAG | VerifyMlagStatus | Verifies the health status of the MLAG configuration. | ✅&nbsp;Success | - |
| c3-leaf1 | Routing | VerifyRoutingProtocolModel | Verifies the configured routing protocol model. | ✅&nbsp;Success | - |
| c3-leaf1 | STP | VerifySTPCounters | Verifies there is no errors in STP BPDU packets. | ✅&nbsp;Success | - |
| c3-leaf1 | System | VerifyAgentLogs | Verifies there are no agent crash reports. | ✅&nbsp;Success | - |
| c3-leaf1 | System | VerifyCoredump | Verifies there are no core dump files. | ✅&nbsp;Success | - |
| c3-leaf1 | System | VerifyFileSystemUtilization | Verifies that no partition is utilizing more than 75% of its disk space. | ✅&nbsp;Success | - |
| c3-leaf1 | System | VerifyMaintenance | Verifies that the device is not currently under or entering maintenance. | ✅&nbsp;Success | - |
| c3-leaf1 | System | VerifyMemoryUtilization | Verifies whether the memory utilization is below 75%. | ✅&nbsp;Success | - |
| c3-leaf1 | System | VerifyReloadCause | Verifies the last reload cause of the device. | ✅&nbsp;Success | - |
| c3-leaf1 | VXLAN | VerifyVxlanConfigSanity | Verifies there are no VXLAN config-sanity inconsistencies. | ✅&nbsp;Success | - |
| c3-leaf2 | BGP | VerifyBGPPeerSession | Verifies the session state of BGP peers. | ✅&nbsp;Success | - |
| c3-leaf2 | Configuration | VerifyRunningConfigDiffs | Verifies there is no difference between the running-config and the startup-config. | ✅&nbsp;Success | - |
| c3-leaf2 | Configuration | VerifyZeroTouch | Verifies ZeroTouch is disabled. | ✅&nbsp;Success | - |
| c3-leaf2 | Connectivity | VerifyLLDPNeighbors | Verifies the connection status of the specified LLDP (Link Layer Discovery Protocol) neighbors. | ✅&nbsp;Success | - |
| c3-leaf2 | Connectivity | VerifyReachability | Verifies point-to-point reachability between Ethernet interfaces. | ✅&nbsp;Success | - |
| c3-leaf2 | Interfaces | VerifyIllegalLACP | Verifies there are no illegal LACP packets in port channels. | ✅&nbsp;Success | - |
| c3-leaf2 | Interfaces | VerifyInterfaceDiscards | Verifies that the interfaces packet discard counters are equal to zero. | ✅&nbsp;Success | - |
| c3-leaf2 | Interfaces | VerifyInterfaceErrDisabled | Verifies there are no interfaces in the errdisabled state. | ✅&nbsp;Success | - |
| c3-leaf2 | Interfaces | VerifyInterfaceErrors | Verifies that the interfaces error counters are equal to zero. | ✅&nbsp;Success | - |
| c3-leaf2 | Interfaces | VerifyInterfaceUtilization | Verifies that the utilization of interfaces is below a certain threshold. | ✅&nbsp;Success | - |
| c3-leaf2 | Interfaces | VerifyInterfacesStatus | Verifies the operational states of specified interfaces to ensure they match expected configurations. | ✅&nbsp;Success | - |
| c3-leaf2 | Interfaces | VerifyPortChannels | Verifies there are no inactive ports in port channels. | ✅&nbsp;Success | - |
| c3-leaf2 | MLAG | VerifyMlagConfigSanity | Verifies there are no MLAG config-sanity inconsistencies. | ✅&nbsp;Success | - |
| c3-leaf2 | MLAG | VerifyMlagInterfaces | Verifies there are no inactive or active-partial MLAG ports. | ✅&nbsp;Success | - |
| c3-leaf2 | MLAG | VerifyMlagStatus | Verifies the health status of the MLAG configuration. | ✅&nbsp;Success | - |
| c3-leaf2 | Routing | VerifyRoutingProtocolModel | Verifies the configured routing protocol model. | ✅&nbsp;Success | - |
| c3-leaf2 | STP | VerifySTPCounters | Verifies there is no errors in STP BPDU packets. | ✅&nbsp;Success | - |
| c3-leaf2 | System | VerifyAgentLogs | Verifies there are no agent crash reports. | ✅&nbsp;Success | - |
| c3-leaf2 | System | VerifyCoredump | Verifies there are no core dump files. | ✅&nbsp;Success | - |
| c3-leaf2 | System | VerifyFileSystemUtilization | Verifies that no partition is utilizing more than 75% of its disk space. | ✅&nbsp;Success | - |
| c3-leaf2 | System | VerifyMaintenance | Verifies that the device is not currently under or entering maintenance. | ✅&nbsp;Success | - |
| c3-leaf2 | System | VerifyMemoryUtilization | Verifies whether the memory utilization is below 75%. | ✅&nbsp;Success | - |
| c3-leaf2 | System | VerifyReloadCause | Verifies the last reload cause of the device. | ✅&nbsp;Success | - |
| c3-leaf2 | VXLAN | VerifyVxlanConfigSanity | Verifies there are no VXLAN config-sanity inconsistencies. | ✅&nbsp;Success | - |
| c3-leaf3 | BGP | VerifyBGPPeerSession | Verifies the session state of BGP peers. | ✅&nbsp;Success | - |
| c3-leaf3 | Configuration | VerifyRunningConfigDiffs | Verifies there is no difference between the running-config and the startup-config. | ✅&nbsp;Success | - |
| c3-leaf3 | Configuration | VerifyZeroTouch | Verifies ZeroTouch is disabled. | ✅&nbsp;Success | - |
| c3-leaf3 | Connectivity | VerifyLLDPNeighbors | Verifies the connection status of the specified LLDP (Link Layer Discovery Protocol) neighbors. | ✅&nbsp;Success | - |
| c3-leaf3 | Connectivity | VerifyReachability | Verifies point-to-point reachability between Ethernet interfaces. | ✅&nbsp;Success | - |
| c3-leaf3 | Interfaces | VerifyIllegalLACP | Verifies there are no illegal LACP packets in port channels. | ✅&nbsp;Success | - |
| c3-leaf3 | Interfaces | VerifyInterfaceDiscards | Verifies that the interfaces packet discard counters are equal to zero. | ✅&nbsp;Success | - |
| c3-leaf3 | Interfaces | VerifyInterfaceErrDisabled | Verifies there are no interfaces in the errdisabled state. | ✅&nbsp;Success | - |
| c3-leaf3 | Interfaces | VerifyInterfaceErrors | Verifies that the interfaces error counters are equal to zero. | ✅&nbsp;Success | - |
| c3-leaf3 | Interfaces | VerifyInterfaceUtilization | Verifies that the utilization of interfaces is below a certain threshold. | ✅&nbsp;Success | - |
| c3-leaf3 | Interfaces | VerifyInterfacesStatus | Verifies the operational states of specified interfaces to ensure they match expected configurations. | ✅&nbsp;Success | - |
| c3-leaf3 | Interfaces | VerifyPortChannels | Verifies there are no inactive ports in port channels. | ✅&nbsp;Success | - |
| c3-leaf3 | MLAG | VerifyMlagConfigSanity | Verifies there are no MLAG config-sanity inconsistencies. | ✅&nbsp;Success | - |
| c3-leaf3 | MLAG | VerifyMlagInterfaces | Verifies there are no inactive or active-partial MLAG ports. | ✅&nbsp;Success | - |
| c3-leaf3 | MLAG | VerifyMlagStatus | Verifies the health status of the MLAG configuration. | ✅&nbsp;Success | - |
| c3-leaf3 | Routing | VerifyRoutingProtocolModel | Verifies the configured routing protocol model. | ✅&nbsp;Success | - |
| c3-leaf3 | STP | VerifySTPCounters | Verifies there is no errors in STP BPDU packets. | ✅&nbsp;Success | - |
| c3-leaf3 | System | VerifyAgentLogs | Verifies there are no agent crash reports. | ✅&nbsp;Success | - |
| c3-leaf3 | System | VerifyCoredump | Verifies there are no core dump files. | ✅&nbsp;Success | - |
| c3-leaf3 | System | VerifyFileSystemUtilization | Verifies that no partition is utilizing more than 75% of its disk space. | ✅&nbsp;Success | - |
| c3-leaf3 | System | VerifyMaintenance | Verifies that the device is not currently under or entering maintenance. | ✅&nbsp;Success | - |
| c3-leaf3 | System | VerifyMemoryUtilization | Verifies whether the memory utilization is below 75%. | ✅&nbsp;Success | - |
| c3-leaf3 | System | VerifyReloadCause | Verifies the last reload cause of the device. | ✅&nbsp;Success | - |
| c3-leaf3 | VXLAN | VerifyVxlanConfigSanity | Verifies there are no VXLAN config-sanity inconsistencies. | ✅&nbsp;Success | - |
| c3-leaf4 | BGP | VerifyBGPPeerSession | Verifies the session state of BGP peers. | ✅&nbsp;Success | - |
| c3-leaf4 | Configuration | VerifyRunningConfigDiffs | Verifies there is no difference between the running-config and the startup-config. | ✅&nbsp;Success | - |
| c3-leaf4 | Configuration | VerifyZeroTouch | Verifies ZeroTouch is disabled. | ✅&nbsp;Success | - |
| c3-leaf4 | Connectivity | VerifyLLDPNeighbors | Verifies the connection status of the specified LLDP (Link Layer Discovery Protocol) neighbors. | ✅&nbsp;Success | - |
| c3-leaf4 | Connectivity | VerifyReachability | Verifies point-to-point reachability between Ethernet interfaces. | ✅&nbsp;Success | - |
| c3-leaf4 | Interfaces | VerifyIllegalLACP | Verifies there are no illegal LACP packets in port channels. | ✅&nbsp;Success | - |
| c3-leaf4 | Interfaces | VerifyInterfaceDiscards | Verifies that the interfaces packet discard counters are equal to zero. | ✅&nbsp;Success | - |
| c3-leaf4 | Interfaces | VerifyInterfaceErrDisabled | Verifies there are no interfaces in the errdisabled state. | ✅&nbsp;Success | - |
| c3-leaf4 | Interfaces | VerifyInterfaceErrors | Verifies that the interfaces error counters are equal to zero. | ✅&nbsp;Success | - |
| c3-leaf4 | Interfaces | VerifyInterfaceUtilization | Verifies that the utilization of interfaces is below a certain threshold. | ✅&nbsp;Success | - |
| c3-leaf4 | Interfaces | VerifyInterfacesStatus | Verifies the operational states of specified interfaces to ensure they match expected configurations. | ✅&nbsp;Success | - |
| c3-leaf4 | Interfaces | VerifyPortChannels | Verifies there are no inactive ports in port channels. | ✅&nbsp;Success | - |
| c3-leaf4 | MLAG | VerifyMlagConfigSanity | Verifies there are no MLAG config-sanity inconsistencies. | ✅&nbsp;Success | - |
| c3-leaf4 | MLAG | VerifyMlagInterfaces | Verifies there are no inactive or active-partial MLAG ports. | ✅&nbsp;Success | - |
| c3-leaf4 | MLAG | VerifyMlagStatus | Verifies the health status of the MLAG configuration. | ✅&nbsp;Success | - |
| c3-leaf4 | Routing | VerifyRoutingProtocolModel | Verifies the configured routing protocol model. | ✅&nbsp;Success | - |
| c3-leaf4 | STP | VerifySTPCounters | Verifies there is no errors in STP BPDU packets. | ✅&nbsp;Success | - |
| c3-leaf4 | System | VerifyAgentLogs | Verifies there are no agent crash reports. | ✅&nbsp;Success | - |
| c3-leaf4 | System | VerifyCoredump | Verifies there are no core dump files. | ✅&nbsp;Success | - |
| c3-leaf4 | System | VerifyFileSystemUtilization | Verifies that no partition is utilizing more than 75% of its disk space. | ✅&nbsp;Success | - |
| c3-leaf4 | System | VerifyMaintenance | Verifies that the device is not currently under or entering maintenance. | ✅&nbsp;Success | - |
| c3-leaf4 | System | VerifyMemoryUtilization | Verifies whether the memory utilization is below 75%. | ✅&nbsp;Success | - |
| c3-leaf4 | System | VerifyReloadCause | Verifies the last reload cause of the device. | ✅&nbsp;Success | - |
| c3-leaf4 | VXLAN | VerifyVxlanConfigSanity | Verifies there are no VXLAN config-sanity inconsistencies. | ✅&nbsp;Success | - |
| c3-leaf5 | BGP | VerifyBGPPeerSession | Verifies the session state of BGP peers. | ✅&nbsp;Success | - |
| c3-leaf5 | Configuration | VerifyRunningConfigDiffs | Verifies there is no difference between the running-config and the startup-config. | ✅&nbsp;Success | - |
| c3-leaf5 | Configuration | VerifyZeroTouch | Verifies ZeroTouch is disabled. | ✅&nbsp;Success | - |
| c3-leaf5 | Connectivity | VerifyLLDPNeighbors | Verifies the connection status of the specified LLDP (Link Layer Discovery Protocol) neighbors. | ✅&nbsp;Success | - |
| c3-leaf5 | Connectivity | VerifyReachability | Verifies point-to-point reachability between Ethernet interfaces. | ✅&nbsp;Success | - |
| c3-leaf5 | Interfaces | VerifyIllegalLACP | Verifies there are no illegal LACP packets in port channels. | ✅&nbsp;Success | - |
| c3-leaf5 | Interfaces | VerifyInterfaceDiscards | Verifies that the interfaces packet discard counters are equal to zero. | ✅&nbsp;Success | - |
| c3-leaf5 | Interfaces | VerifyInterfaceErrDisabled | Verifies there are no interfaces in the errdisabled state. | ✅&nbsp;Success | - |
| c3-leaf5 | Interfaces | VerifyInterfaceErrors | Verifies that the interfaces error counters are equal to zero. | ✅&nbsp;Success | - |
| c3-leaf5 | Interfaces | VerifyInterfaceUtilization | Verifies that the utilization of interfaces is below a certain threshold. | ✅&nbsp;Success | - |
| c3-leaf5 | Interfaces | VerifyInterfacesStatus | Verifies the operational states of specified interfaces to ensure they match expected configurations. | ✅&nbsp;Success | - |
| c3-leaf5 | Interfaces | VerifyPortChannels | Verifies there are no inactive ports in port channels. | ✅&nbsp;Success | - |
| c3-leaf5 | MLAG | VerifyMlagConfigSanity | Verifies there are no MLAG config-sanity inconsistencies. | ✅&nbsp;Success | - |
| c3-leaf5 | MLAG | VerifyMlagInterfaces | Verifies there are no inactive or active-partial MLAG ports. | ✅&nbsp;Success | - |
| c3-leaf5 | MLAG | VerifyMlagStatus | Verifies the health status of the MLAG configuration. | ✅&nbsp;Success | - |
| c3-leaf5 | Routing | VerifyRoutingProtocolModel | Verifies the configured routing protocol model. | ✅&nbsp;Success | - |
| c3-leaf5 | STP | VerifySTPCounters | Verifies there is no errors in STP BPDU packets. | ✅&nbsp;Success | - |
| c3-leaf5 | System | VerifyAgentLogs | Verifies there are no agent crash reports. | ✅&nbsp;Success | - |
| c3-leaf5 | System | VerifyCoredump | Verifies there are no core dump files. | ✅&nbsp;Success | - |
| c3-leaf5 | System | VerifyFileSystemUtilization | Verifies that no partition is utilizing more than 75% of its disk space. | ✅&nbsp;Success | - |
| c3-leaf5 | System | VerifyMaintenance | Verifies that the device is not currently under or entering maintenance. | ✅&nbsp;Success | - |
| c3-leaf5 | System | VerifyMemoryUtilization | Verifies whether the memory utilization is below 75%. | ✅&nbsp;Success | - |
| c3-leaf5 | System | VerifyReloadCause | Verifies the last reload cause of the device. | ✅&nbsp;Success | - |
| c3-leaf5 | VXLAN | VerifyVxlanConfigSanity | Verifies there are no VXLAN config-sanity inconsistencies. | ✅&nbsp;Success | - |
| c3-leaf6 | BGP | VerifyBGPPeerSession | Verifies the session state of BGP peers. | ✅&nbsp;Success | - |
| c3-leaf6 | Configuration | VerifyRunningConfigDiffs | Verifies there is no difference between the running-config and the startup-config. | ✅&nbsp;Success | - |
| c3-leaf6 | Configuration | VerifyZeroTouch | Verifies ZeroTouch is disabled. | ✅&nbsp;Success | - |
| c3-leaf6 | Connectivity | VerifyLLDPNeighbors | Verifies the connection status of the specified LLDP (Link Layer Discovery Protocol) neighbors. | ✅&nbsp;Success | - |
| c3-leaf6 | Connectivity | VerifyReachability | Verifies point-to-point reachability between Ethernet interfaces. | ✅&nbsp;Success | - |
| c3-leaf6 | Interfaces | VerifyIllegalLACP | Verifies there are no illegal LACP packets in port channels. | ✅&nbsp;Success | - |
| c3-leaf6 | Interfaces | VerifyInterfaceDiscards | Verifies that the interfaces packet discard counters are equal to zero. | ✅&nbsp;Success | - |
| c3-leaf6 | Interfaces | VerifyInterfaceErrDisabled | Verifies there are no interfaces in the errdisabled state. | ✅&nbsp;Success | - |
| c3-leaf6 | Interfaces | VerifyInterfaceErrors | Verifies that the interfaces error counters are equal to zero. | ✅&nbsp;Success | - |
| c3-leaf6 | Interfaces | VerifyInterfaceUtilization | Verifies that the utilization of interfaces is below a certain threshold. | ✅&nbsp;Success | - |
| c3-leaf6 | MLAG | VerifyMlagConfigSanity | Verifies there are no MLAG config-sanity inconsistencies. | ✅&nbsp;Success | - |
| c3-leaf6 | MLAG | VerifyMlagInterfaces | Verifies there are no inactive or active-partial MLAG ports. | ✅&nbsp;Success | - |
| c3-leaf6 | MLAG | VerifyMlagStatus | Verifies the health status of the MLAG configuration. | ✅&nbsp;Success | - |
| c3-leaf6 | Routing | VerifyRoutingProtocolModel | Verifies the configured routing protocol model. | ✅&nbsp;Success | - |
| c3-leaf6 | STP | VerifySTPCounters | Verifies there is no errors in STP BPDU packets. | ✅&nbsp;Success | - |
| c3-leaf6 | System | VerifyAgentLogs | Verifies there are no agent crash reports. | ✅&nbsp;Success | - |
| c3-leaf6 | System | VerifyCoredump | Verifies there are no core dump files. | ✅&nbsp;Success | - |
| c3-leaf6 | System | VerifyFileSystemUtilization | Verifies that no partition is utilizing more than 75% of its disk space. | ✅&nbsp;Success | - |
| c3-leaf6 | System | VerifyMaintenance | Verifies that the device is not currently under or entering maintenance. | ✅&nbsp;Success | - |
| c3-leaf6 | System | VerifyMemoryUtilization | Verifies whether the memory utilization is below 75%. | ✅&nbsp;Success | - |
| c3-leaf6 | System | VerifyReloadCause | Verifies the last reload cause of the device. | ✅&nbsp;Success | - |
| c3-leaf6 | VXLAN | VerifyVxlanConfigSanity | Verifies there are no VXLAN config-sanity inconsistencies. | ✅&nbsp;Success | - |
| c3-spine1 | BGP | VerifyBGPPeerSession | Verifies the session state of BGP peers. | ✅&nbsp;Success | - |
| c3-spine1 | Configuration | VerifyRunningConfigDiffs | Verifies there is no difference between the running-config and the startup-config. | ✅&nbsp;Success | - |
| c3-spine1 | Configuration | VerifyZeroTouch | Verifies ZeroTouch is disabled. | ✅&nbsp;Success | - |
| c3-spine1 | Connectivity | VerifyLLDPNeighbors | Verifies the connection status of the specified LLDP (Link Layer Discovery Protocol) neighbors. | ✅&nbsp;Success | - |
| c3-spine1 | Connectivity | VerifyReachability | Verifies point-to-point reachability between Ethernet interfaces. | ✅&nbsp;Success | - |
| c3-spine1 | Interfaces | VerifyInterfaceDiscards | Verifies that the interfaces packet discard counters are equal to zero. | ✅&nbsp;Success | - |
| c3-spine1 | Interfaces | VerifyInterfaceErrDisabled | Verifies there are no interfaces in the errdisabled state. | ✅&nbsp;Success | - |
| c3-spine1 | Interfaces | VerifyInterfaceErrors | Verifies that the interfaces error counters are equal to zero. | ✅&nbsp;Success | - |
| c3-spine1 | Interfaces | VerifyInterfaceUtilization | Verifies that the utilization of interfaces is below a certain threshold. | ✅&nbsp;Success | - |
| c3-spine1 | Interfaces | VerifyInterfacesStatus | Verifies the operational states of specified interfaces to ensure they match expected configurations. | ✅&nbsp;Success | - |
| c3-spine1 | Routing | VerifyRoutingProtocolModel | Verifies the configured routing protocol model. | ✅&nbsp;Success | - |
| c3-spine1 | STP | VerifySTPCounters | Verifies there is no errors in STP BPDU packets. | ✅&nbsp;Success | - |
| c3-spine1 | System | VerifyAgentLogs | Verifies there are no agent crash reports. | ✅&nbsp;Success | - |
| c3-spine1 | System | VerifyCoredump | Verifies there are no core dump files. | ✅&nbsp;Success | - |
| c3-spine1 | System | VerifyFileSystemUtilization | Verifies that no partition is utilizing more than 75% of its disk space. | ✅&nbsp;Success | - |
| c3-spine1 | System | VerifyMaintenance | Verifies that the device is not currently under or entering maintenance. | ✅&nbsp;Success | - |
| c3-spine1 | System | VerifyMemoryUtilization | Verifies whether the memory utilization is below 75%. | ✅&nbsp;Success | - |
| c3-spine1 | System | VerifyReloadCause | Verifies the last reload cause of the device. | ✅&nbsp;Success | - |
| c3-spine2 | BGP | VerifyBGPPeerSession | Verifies the session state of BGP peers. | ✅&nbsp;Success | - |
| c3-spine2 | Configuration | VerifyRunningConfigDiffs | Verifies there is no difference between the running-config and the startup-config. | ✅&nbsp;Success | - |
| c3-spine2 | Configuration | VerifyZeroTouch | Verifies ZeroTouch is disabled. | ✅&nbsp;Success | - |
| c3-spine2 | Connectivity | VerifyLLDPNeighbors | Verifies the connection status of the specified LLDP (Link Layer Discovery Protocol) neighbors. | ✅&nbsp;Success | - |
| c3-spine2 | Connectivity | VerifyReachability | Verifies point-to-point reachability between Ethernet interfaces. | ✅&nbsp;Success | - |
| c3-spine2 | Interfaces | VerifyInterfaceDiscards | Verifies that the interfaces packet discard counters are equal to zero. | ✅&nbsp;Success | - |
| c3-spine2 | Interfaces | VerifyInterfaceErrDisabled | Verifies there are no interfaces in the errdisabled state. | ✅&nbsp;Success | - |
| c3-spine2 | Interfaces | VerifyInterfaceErrors | Verifies that the interfaces error counters are equal to zero. | ✅&nbsp;Success | - |
| c3-spine2 | Interfaces | VerifyInterfaceUtilization | Verifies that the utilization of interfaces is below a certain threshold. | ✅&nbsp;Success | - |
| c3-spine2 | Interfaces | VerifyInterfacesStatus | Verifies the operational states of specified interfaces to ensure they match expected configurations. | ✅&nbsp;Success | - |
| c3-spine2 | Routing | VerifyRoutingProtocolModel | Verifies the configured routing protocol model. | ✅&nbsp;Success | - |
| c3-spine2 | STP | VerifySTPCounters | Verifies there is no errors in STP BPDU packets. | ✅&nbsp;Success | - |
| c3-spine2 | System | VerifyAgentLogs | Verifies there are no agent crash reports. | ✅&nbsp;Success | - |
| c3-spine2 | System | VerifyCoredump | Verifies there are no core dump files. | ✅&nbsp;Success | - |
| c3-spine2 | System | VerifyFileSystemUtilization | Verifies that no partition is utilizing more than 75% of its disk space. | ✅&nbsp;Success | - |
| c3-spine2 | System | VerifyMaintenance | Verifies that the device is not currently under or entering maintenance. | ✅&nbsp;Success | - |
| c3-spine2 | System | VerifyMemoryUtilization | Verifies whether the memory utilization is below 75%. | ✅&nbsp;Success | - |
| c3-spine2 | System | VerifyReloadCause | Verifies the last reload cause of the device. | ✅&nbsp;Success | - |
