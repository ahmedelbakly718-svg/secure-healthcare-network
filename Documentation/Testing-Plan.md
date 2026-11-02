# Testing Plan

## 1. Introduction
This document defines the proposed testing procedures for validating the secure healthcare network infrastructure.

## 2. Testing Objectives
- Verify network connectivity.
- Validate IP addressing and VLAN configuration.
- Evaluate access control policies.
- Verify isolation between authorized and unauthorized network segments.
- Document test results and identified issues.

## 3. Testing Environment
The network will be tested using Cisco Packet Tracer with simulated routers, switches, servers, and end-user devices.

## 4. Test Cases

### Test Case 1: IP Address Configuration
**Objective:** Verify that network devices have the correct IP configuration.
**Expected Result:** Each device uses an address from its assigned subnet.

### Test Case 2: Department Connectivity
**Objective:** Verify connectivity between devices within the same authorized VLAN.
**Expected Result:** Devices communicate according to the network design.

### Test Case 3: Inter-VLAN Communication
**Objective:** Verify routing between departmental VLANs.
**Expected Result:** Only communication permitted by the security policy succeeds.

### Test Case 4: DHCP Service
**Objective:** Verify automatic IP address assignment.
**Expected Result:** Clients receive valid IP configuration from the DHCP service.

### Test Case 5: Server Access Control
**Objective:** Verify access restrictions for healthcare servers.
**Expected Result:** Authorized devices can access approved services; unauthorized access is denied.

### Test Case 6: Guest Network Isolation
**Objective:** Verify separation of guest Wi-Fi from internal hospital systems.
**Expected Result:** Guest devices cannot access restricted internal resources.

### Test Case 7: Network Availability
**Objective:** Check connectivity after the network configuration is completed.
**Expected Result:** Required network services remain reachable under the defined test conditions.

## 5. Test Results Record
For each test, record:
- Test case identifier.
- Test date.
- Configuration tested.
- Actual result.
- Status: Pass, Fail, or Not Tested.
- Notes and corrective actions.

## 6. Acceptance Criteria
The network design will be considered validated when required connectivity works, access restrictions behave as intended, and all test outcomes are documented.

## 7. Conclusion
This testing plan provides a structured method for evaluating network functionality and security in the simulation environment.

Note: These are planned tests. Results must be recorded only after the tests are actually performed.
