<script setup lang="ts">
</script>

<template>
  <div class="bgc">
    <div class="notes">
      <div class="name">吕超</div>
      <div class="header">
        <div class="headerItem">
          <div class="headerLabel">年龄：</div>
          <div class="headerValue">26</div>
        </div>
        <div class="headerItem">
          <div class="headerLabel">性别：</div>
          <div class="headerValue">男</div>
        </div>
        <div class="headerItem">
          <div class="headerLabel">电话：</div>
          <div class="headerValue">18735674692</div>
        </div>
        <div class="headerItem">
          <div class="headerLabel">邮箱：</div>
          <div class="headerValue">1969956387@qq.com</div>
        </div>
      </div>
      <div class="title">
        教育背景
      </div>
      <div class="edu content">
        <div class="schoolName">山西工程技术学院</div>
        <div class="subject">计算机科学与技术</div>
        <div class="time">2020.6</div>
      </div>
      <div class="title">
        专业技能
      </div>
      <div class="content skills">
        <ul>
          <li>熟练掌握 HTML/CSS/javascript 等前端技术，能写出符合W3C标准的代码。</li>
          <li>熟练 javascript 以及 ES6 新特新，js 常用库如 lodash、Echarts、axios、ant-design、element-ui； css3 新特性；html5 新特性等。</li>
          <li>熟练使用 vue2、vue-router、vuex 技术开发，熟悉 vue3 新技术，并由实际开发经验。</li>
          <li>熟练使用 git 版本工具进行代码控制与写作，能手动部署项目。</li>
          <li>具有组件化、模块化的思想，能根据需求，基建组件开发，高效支撑业务。</li>
        </ul>
      </div>
      <div class="title">
        工作经验
      </div>
      <div class="content job">
        <div class="item">
          <div class="jobInfo">
            <div class="box">百融云创</div>
            <div class="box">中级研发工程师</div>
            <div class="box">2020-08-09 至 2023-03-06</div>
          </div>
          <ul>
            <li>参与产品前端技术选型，根据需求评估开发周期，前端架构设计，代码优化，</li>
            <li>遵循和优化公司编码规范并负责编码实现，参与产品前端性能优化，故障排查和解决。</li>
            <li>与后端同事一起落地产品，负责系统的操作手册以及安装部署手册等。</li>
            <li>学习前沿的互联网技术，对公司产品进行创新，及时把新技术转化为业务中的生产力。</li>
          </ul>
        </div>
        <div class="item">
          <div class="jobInfo">
            <div class="box">简巨科技</div>
            <div class="box">中级研发工程师</div>
            <div class="box">2020-08-09 至 2023-03-06</div>
          </div>
          <ul>
            <li>参与产品前端技术选型，根据需求评估开发周期，前端架构设计，代码优化，</li>
            <li>遵循和优化公司编码规范并负责编码实现，参与产品前端性能优化，故障排查和解决。</li>
            <li>与后端同事一起落地产品，负责系统的操作手册以及安装部署手册等。</li>
            <li>学习前沿的互联网技术，对公司产品进行创新，及时把新技术转化为业务中的生产力。</li>
          </ul>
        </div>
      </div>
      <div class="title">
        项目经验
      </div>
      <div class="content project">
        <div class="projectItem">
          <div class="projectBaseinfo">
            <div class="box">科产担保、小贷系统平台</div>
            <div class="box">百融云创</div>
            <div class="box">2022.3 - 至今</div>
          </div>
          <div class="item">
            <div class="desc">
              项目描述：基于科产的担保贷款和小额贷款两条主业务线，实现了由线上录入数据，在线签署合同，流程跟踪放款，贷后风控决策引擎，风控报备，以及代偿追偿整条业务线。在整条业务线中，加入bpm工作流，并且提供pc和app两种方式实现在线审批，对科产公司的业务实现了线上化，标准化，高效化。
            </div>
            <div class="technicalPoints">
              技术要点
              <ul>
                <li>技术栈采用 vue2、vue-router、vuex、vue-cli、element-ui、axios 等等。</li>
                <li>根据实际需求，讨论、设计及实现项目通用组件，覆盖80%页面使用。</li>
                <li>通过 iframe 方式实现bpm系统和业务系统之间的页面嵌入，以及两系统之间的通信，实际落地公司的产品。</li>
                <li>利用同源cookie的特性，实现多系统单点登录的功能。</li>
              </ul>
            </div>
            <div class="projectRespon">
              项目职责
                <ul>
                  <li>根据业务需求，按时保质开发业务代码。</li>
                  <li>根据产品需求，封装高复用、维护性，扩展性良好的通用前端组件，落实组件的使用文档并内部推广。</li>
                  <li>积极主动和项目组其他相关人员沟通解决问题。</li>
                </ul>
            </div>
          </div>
        </div>
        <div class="projectItem">
          <div class="projectBaseinfo">
            <div class="box">科产官网</div>
            <div class="box">百融云创</div>
            <div class="box">2022.03 - 2022.03</div>
          </div>
          <div class="item">
            <div class="desc">
              项目描述：对外展示科产公司的介绍，包含公司介绍、产品、动态、政策、留言功能。后台支持产品、动态和政策的实时更新。
            </div>
            <div class="technicalPoints">
              技术要点
              <ul>
                <li>前端使用 nuxtjs 实现；后台使用 vue3、typeScript、element-plus、axios 开发；后端采用 egg、mysql 开发。</li>
                <li>前端使用 nuxtjs ssr 模式渲染、seo 优化。</li>
                <li>根据业务需求出发，后端采用 配置、 egg-jwt 、中间件 的方式实现接口权限的校验和登录的校验。</li>
              </ul>
            </div>
            <div class="projectRespon">
              项目职责
                <ul>
                  <li>主动和相关人员沟通，评估开发技术栈、开发周期，数据库设计和项目设计评审。</li>
                  <li>根据业务需求开发前端、后台、后端业务代码。</li>
                  <li>编写前端、后台、后端的项目结构介绍文档、服务器配置信息文档、安装和部署手册。</li>
                </ul>
            </div>
          </div>
        </div>
        <div class="projectItem">
          <div class="projectBaseinfo">
            <div class="box">担保、小贷大屏展示</div>
            <div class="box">百融云创</div>
            <div class="box">2022.07 - 2022.08</div>
          </div>
          <div class="item">
            <div class="desc">
              项目描述：以大屏为载体，将担保、小贷的统计数据以视觉冲击、图表的方式呈现给客户。
            </div>
            <div class="technicalPoints">
              技术要点
              <ul>
                <li>通过 transform: scale 的方式适应大屏的展示。</li>
                <li>使用 websocket 实时更新业务数据数值。</li>
              </ul>
            </div>
            <div class="projectRespon">
              项目职责
                <ul>
                  <li>根据项目需求、ui设计稿，1：1 自适应的还原设计稿。</li>
                  <li>和后端联调接口</li>
                </ul>
            </div>
          </div>
        </div>
        <div class="projectItem">
          <div class="projectBaseinfo">
            <div class="box">云gis空间库</div>
            <div class="box">简巨科技</div>
            <div class="box">2022.03 - 2022.03</div>
          </div>
          <div class="item">
            <div class="desc">
              项目描述：基于 mapbox 技术，以主题地图为单位，在二维地图上支撑编辑地理信息资源，在线编辑，保存，回显。以工具箱的形式补充扩展云计算的功能。以一种更加友好的方式，高效率、低成本的使用地理信息资源。
            </div>
            <div class="technicalPoints">
              技术要点
              <ul>
                <li>采用 vue2、mapbox、element-ui 技术栈开发。</li>
                <li>设计并实现 mapbox 数据解析 map 类，实现主题地图回显时的数据解析、编辑保存时的数据转换功能。</li>
                <li>基于不同点、线、面不同数据，不同图层绘制工具的需求，设计封装 原子类工具、绘制图层工具。</li>
              </ul>
            </div>
            <div class="projectRespon">
              项目职责
                <ul>
                  <li>与相关开发人员沟通，讨论、设计地图数据的存储格式，设计实现 map 数据解析类。</li>
                  <li>根据业务需求，设计、实现，可扩展维护，以原子组件为基本，组合的方式形成的通用业务组件。</li>
                  <li>根据项目需求，ui设计稿，按时完成业务代码。</li>
                </ul>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped lang="scss">
.bgc {
  background-color: #000;
  min-height: 100vh;
}
.notes {
  width: 1000px;
  padding: 20px 40px;
  background-color: #fff;

  .name {
    height: 36px;
    line-height: 36px;
    letter-spacing: 5px;
    font-size: 24px;
    font-weight: 700;
    color: #284967;
  }

  .header {
    margin-top: 15px;
    width: 60%;
    display: flex;
    flex-wrap: wrap;
    .headerItem {
      width: 49%;
      line-height: 1.8em;
      display: flex;

      .headerLabel {
        width: 80px;
      }
    }
  }

  .title {
    margin: 25px 0 0;
    font-size: 15px;
    color: #284967;
    line-height: 28px;
    padding-left: 10px;
    font-weight: 600;
    background-color: rgba(40,73,103,0.12);
  }

  .content {
    margin: 10px;
  }

  .edu {
    display: flex;
    color: #333;;

    .subject,
    .schoolName {
      flex: 1;
      text-align: left;
    }
  }
}
</style>
