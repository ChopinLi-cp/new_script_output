io.jboot.components.cache.JbootCacheManager.me

```java
<io.jboot.components.cache.JbootCacheManager>
  <cacheMap class="concurrent-hash-map">
    <entry>
      <key class="string">redis</key>
      <value class="io.jboot.components.cache.redis.JbootRedisCacheImpl">
        <redis class="io.jboot.support.redis.jedis.JbootJedisImpl">
          <close>false</close>
          <config class="io.jboot.components.cache.redis.JbootRedisCacheConfig">
            <host>127.0.0.1</host>
            <port>6379</port>
            <timeout>2000</timeout>
            <type>jedis</type>
          </config>
          <jedisPool>
            <internalPool>
              <activeTimes>
                <index>0</index>
                <size>100</size>
                <outer-class class="org.apache.commons.pool2.impl.GenericObjectPool" reference="/io.jboot.components.cache.JbootCacheManager/cacheMap/entry/value/redis/jedisPool/internalPool"/>
                <values>
                  <java.util.concurrent.atomic.AtomicLong>
                    <value>-1</value>
                  </java.util.concurrent.atomic.AtomicLong>
....
              <evictionPolicy class="org.apache.commons.pool2.impl.DefaultEvictionPolicy"/>
              <evictor>
                <lock/>
                <nextExecutionTime>0</nextExecutionTime>
                <period>0</period>
                <state>0</state>
                <outer-class class="org.apache.commons.pool2.impl.GenericObjectPool" reference="/io.jboot.components.cache.JbootCacheManager/cacheMap/entry/value/redis/jedisPool/internalPool"/>
              </evictor>
              <evictorShutdownTimeoutMillis>10000</evictorShutdownTimeoutMillis>
              <factory class="redis.clients.jedis.JedisFactory">
                <connectionTimeout>2000</connectionTimeout>
                <database>0</database>
                <hostAndPort>
                  <value class="redis.clients.jedis.HostAndPort">
                    <host>127.0.0.1</host>
                    <port>6379</port>
                  </value>
                </hostAndPort>
                <soTimeout>2000</soTimeout>
                <ssl>false</ssl>
...
								</values>
              </waitTimes>
            </internalPool>
          </jedisPool>
          <serializer class="io.jboot.components.serializer.FstSerializer"/>
        </redis>
      </value>
    </entry>
  </cacheMap>
  <config>
    <aopCacheLiveSeconds>0</aopCacheLiveSeconds>
    <type>redis</type>
  </config>
</io.jboot.components.cache.JbootCacheManager>
```

apache.shardingsphere.elasticjob.cloud.scheduler.mesos.AppConstraintEvaluator.instance.xml

```java
<org.apache.shardingsphere.elasticjob.cloud.scheduler.mesos.AppConstraintEvaluator>
  <facadeService/>
  <runningApps/>
</org.apache.shardingsphere.elasticjob.cloud.scheduler.mesos.AppConstraintEvaluator>
```

```java
<org.apache.shardingsphere.elasticjob.cloud.scheduler.mesos.AppConstraintEvaluator>
  <facadeService/>
  <runningApps/>
</org.apache.shardingsphere.elasticjob.cloud.scheduler.mesos.AppConstraintEvaluator>
```

org.apache.shardingsphere.elasticjob.cloud.scheduler.mesos.AppConstraintEvaluatorTest.facadeService

```java
<org.apache.shardingsphere.elasticjob.cloud.scheduler.mesos.FacadeService/>
```

```java
<org.apache.shardingsphere.elasticjob.cloud.scheduler.mesos.FacadeService/>
```
