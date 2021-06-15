# ngx_http_flv_live_module

Media streaming server based on nginx-rtmp-module. In addtion to the features nginx-rtmp-module provides, HTTP-FLV, GOP cache and VHOST (one IP for multi domain names) are supported now.

- Official: https://github.com/winshining/nginx-http-flv-module
- Build: https://github.com/nginx-with-docker/nginx-http-flv-module-src
## Nginx Images

<table>
    <thead>
        <tr>
            <th>Nginx Version</th>
            <th>Module Version</th>
            <th>Docker Images</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>1.21.0</td>
            <td>1.2.9</td>
            <td><ul>
                <li>docker pull soulteary/prebuilt-nginx-modules:ngx-1.21.0-flv-live-1.2.9</li>
                <li>docker pull soulteary/prebuilt-nginx-modules:ngx-1.21.0-flv-live-1.2.9-alpine</li>
            </ul></td>
        </tr>
    </tbody>
</table>

## TODO

- try merge changes: https://github.com/winshining/nginx-http-flv-module/pulls
