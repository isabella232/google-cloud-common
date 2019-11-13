---
name: GA Checklist
about: Track the tasks for taking a library to GA

---

### Generator
- [ ] Producing Beta or GA artifacts (such that the derived surface should be mostly stable like manual surfaces).
- [ ] Integration test for all generator features used by this API must be running (can be against a different API)
- [ ] Tests for all code-generator features in use by the API should have been run at least as a one-of on all supported platforms (Linux, OS X, Windows)
- [ ] Passed a performance test on a representative API
- [ ] No open performance issues of high severity

### API
- [ ] Server API is GA

### Features / surface
- [ ] Server functionality should be fully exposed
- [ ] Surface should be stable with a backward compatibility commitment

### Samples
- [ ] Public code-gen methods must have usable generated samples in the doc comments

### Documentation
- [ ] Code-gen methods must have generated documentation published
- [ ] The client library must have useful, descriptive documentation for any important concepts not adequately covered by the individual method samples or backend API documentation

### Bugs / issues
- [ ] Maintenance of issue trackers for the client library must be meeting SLO

### Build
- [ ] No deterministic failures

### Testing
- [ ] Auto-generated unit tests for all transports should be active and providing 80% code coverage
- [ ] At least one integration/smoke test should be defined and passing
- [ ] Continuous integration and GitHub branch protections must be set up for the API
- [ ] No deterministic failures

### Performance
- [ ] No known high severity performance issues

### GitHub README
- [ ] Central README lists and points to the API
- [ ] Includes a full description of the API
- [ ] Contains at least one “getting started” sample using the most common API scenario

### Cloud Site
- [ ] Client Libraries page must be added to the product documentation in 'APIs & Reference' section of the product's documentation on Cloud Site
- [ ] Client Libraries page must be linked from each per language documentation page in the product documentation on Cloud Site

### Bake time
- [ ] 28 days elapsed since Beta

### Reviews / signoff
- [ ] Code review complete by repo owners
- [ ] DPE surface review complete
- [ ] API team surface review complete
